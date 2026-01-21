👂 Orelha dos Sonhos - Web App
Este projeto é uma aplicação web Mobile-First desenvolvida para o negócio de Furo de Orelha Humanizado da enfermeira Victória Serrano. O objetivo é oferecer uma experiência interativa onde clientes podem agendar serviços, visualizar cuidados pós-furo e, principalmente, experimentar joias virtualmente através de realidade aumentada simples.

🚀 Funcionalidades Principais
1. 🏠 Página Inicial (Hub Central)

Design Interface elegante com botões estilo vidro (Glassmorphism) para acesso rápido a WhatsApp, Instagram, TikTok e Spotify.

Integração com Mapas: Card interativo com mapa embutido e link direto para GPS/Waze.

Identidade Visual: Fundo degradê fixo em Verde Petróleo (#0B464C a #206870) e logo com efeito de brilho pulsante.

2. 📸 Provador Virtual (Câmera & Edição)

A funcionalidade principal do aplicativo (camera.html), permitindo que o usuário visualize como a joia ficará na orelha.

Acesso à Câmera: Utiliza a API navigator.mediaDevices para acessar a câmera traseira (padrão) ou frontal do dispositivo.

Upload de Galeria: Opção de fallback para carregar uma foto da galeria caso o usuário prefira.

Manipulação de Stickers (Joias):

Sistema de "arrastar e soltar" (Drag & Drop) com suporte a toque (touch events).

Controles deslizantes (Sliders) para ajuste preciso de Tamanho e Rotação da joia.

Catálogo de joias carregado dinamicamente.

Ferramenta de Corte (Crop): Permite zoom e re-enquadramento da foto antes da edição.

3. 🖨️ Animação de Impressão (Skeuomorphism)

Ao finalizar a edição na câmera, o app executa uma experiência visual única:

Impressora Virtual: Uma interface realista desenhada puramente com CSS (gradientes metálicos, LEDs piscantes e slot de saída com profundidade).

Animação de Saída: A foto desliza suavemente de "dentro" da impressora virtual, simulando a revelação de uma foto física.

4. 🖼️ Geração de Polaroid & Compartilhamento

Canvas API: A imagem final é gerada via código, combinando:

Fundo degradê da marca.

Moldura estilo Polaroid branca.

A foto do usuário com as joias aplicadas.

Logo e arroba (@orelhadossonhosrp) alinhados no rodapé.

Web Share API: Botão nativo para compartilhar a imagem gerada diretamente no Instagram Stories, WhatsApp, etc.

5. ✨ Páginas Informativas & "Em Breve"

Cuidados: Lista estilizada com ícones e orientações de saúde.

Loja & Cursos: Páginas de espera com um efeito de partículas interativo (JavaScript) onde emojis de orelha (👂) e brilho (✨) flutuam ao passar o mouse ou tocar na tela.

🛠️ Tecnologias e Técnicas Utilizadas
O projeto foi construído utilizando Vanilla Web Technologies (sem frameworks pesados), garantindo leveza e compatibilidade máxima.

HTML5 Semântico: Estrutura acessível e otimizada para SEO.

CSS3 Avançado:

Variáveis CSS (:root) para gerenciamento de tema e cores.

Glassmorphism: Uso intensivo de backdrop-filter: blur() e bordas translúcidas para criar o efeito de vidro fosco.

Skeuomorphism: Design da impressora utilizando múltiplos linear-gradients e sombras para simular metal e luzes reais.

Animações (Keyframes): Usadas para o brilho da logo, o piscar dos LEDs e o movimento de impressão da foto.

Flexbox & Grid: Para layout responsivo.

JavaScript (ES6+):

Manipulação direta do DOM.

Lógica de toque (Touch Events) para dispositivos móveis.

Manipulação de Canvas 2D para renderização de imagem composta.

Gerenciamento de Blobs e URLs de objetos para download/compartilhamento.

🎨 Identidade Visual
Paleta de Cores: Foco em tons de Verde Petróleo (#0B464C, #1F454B) combinados com branco e transparências.

Tipografia:

Títulos: Playfair Display (Serifada, elegante).

Corpo: Raleway (Sans-serif, moderna e limpa).
