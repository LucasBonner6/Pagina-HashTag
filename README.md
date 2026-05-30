# 💻 Clone - Página Principal Hashtag Treinamentos

Um clone de alta fidelidade visual e totalmente responsivo da página inicial da **Hashtag Treinamentos**. O objetivo principal deste projeto foi consolidar práticas avançadas de desenvolvimento front-end, focando em arquitetura CSS modular, otimização de performance de carregamento e design totalmente adaptável para múltiplos dispositivos.

## 📸 Interface do Projeto

![Preview da Home Hashtag](./imagens/preview.png)

## 🔗 Demonstração Online

O projeto foi publicado utilizando o GitHub Pages e pode ser acessado diretamente pelo link abaixo:
👉 [Acessar o Clone da Hashtag ao vivo](https://lucasbonner6.github.io/Pagina-HashTag/)

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica e limpa utilizando tags modernas (`<header>`, `<figure>`, `<nav>`) para garantir boa acessibilidade e SEO.
- **CSS3 Avançado:** \* **Estilização Global:** Separação da base de estilos e resets no arquivo `global.css`.
  - **Design Responsivo Avançado (Breakpoints Dedicados):** Organização cirúrgica de media queries através de arquivos CSS isolados por resolução (`media-480.css`, `media-767.css`, `media-830.css`, `media-1035.css`, `media-1160.css`). Isso garante que a interface quebre de forma perfeita em celulares, tablets e desktops.
- **Otimização de Carregamento (Performance):**
  - Integração de tags `<link rel="preconnect">` e `<link rel="preload">` para acelerar o download de fontes externas (_Montserrat_) e do banner principal (`.webp`).
  - Uso do formato de imagem de última geração **WebP** para reduzir consideravelmente o tamanho dos arquivos de mídia sem perder qualidade visual.
- **Google Fonts:** Tipografia moderna e idêntica ao site original.

## 🚀 Funcionalidades e Diferenciais Técnicos

- 📱 **Arquitetura Mobile-First / Responsiva:** Layout adaptado milimetricamente para as principais resoluções de tela do mercado.
- ⚡ **Performance Otimizada:** Redução do tempo de carregamento da página através do pré-carregamento de recursos críticos e compressão de imagens.
- 🧭 **Menu de Navegação:** Cabeçalho estruturado com links de redirecionamento funcionais e ícones dinâmicos.
