## 🌐 [English Version of README](README_EN.md)

# Jogo Pong com p5.js

Este projeto é uma implementação do clássico jogo Pong utilizando a biblioteca p5.js. O jogo permite que um jogador controle uma raquete para jogar contra o computador, tentando marcar pontos ao fazer a bola passar pela raquete adversária.

## 🔨 Funcionalidades do Projeto

- **Jogabilidade Básica de Pong**: Mova sua raquete verticalmente para rebater a bola.
- **Controle de Raquete Automatizado**: A raquete do computador move-se automaticamente em resposta à posição da bola.
- **Efeitos Sonoros**: Sons são reproduzidos ao rebater a bola e ao marcar pontos.
- **Anúncio de Pontuação via SpeechSynthesis**: A pontuação é anunciada utilizando a API de sintetização de fala.

### Exemplo Visual do Projeto

![chrome-capture-2024-11-23](https://github.com/user-attachments/assets/2ec08361-bde5-4511-9e13-c8751a77fec6)

## ✔️ Técnicas e Tecnologias Utilizadas

- **HTML/CSS**: Estrutura e estilos básicos para a página do jogo.
- **JavaScript**: Lógica do jogo e interações na página.
- **p5.js**: Biblioteca de JavaScript para criação de gráficos e interações interativas.
- **p5.sound**: Extensão da p5.js para manipulação de áudio.

## 📁 Estrutura do Projeto

- **index.html**: Arquivo HTML principal do jogo.
- **sketch.js**: Script JavaScript contendo a lógica principal do jogo.
- **style.css**: Folha de estilos para estilização básica.
- **assets/**:
    - **images/**:
        - `bola.png`: Imagem usada para a bola.
        - `barra01.png`: Imagem usada para a raquete do jogador.
        - `barra02.png`: Imagem usada para a raquete do computador.
    - **sounds/**:
        - `bounce.wav`: Som reproduzido ao rebater a bola.
        - `jingle_win_synth_02.wav`: Som reproduzido ao marcar um ponto.

## 🛠️ Abrir e rodar o projeto

Para iniciar o projeto localmente, siga os passos abaixo:

1. **Certifique-se de que o Node.js está instalado**:
    - O [Node.js](https://nodejs.org/) é necessário para rodar o projeto. Você pode verificar se já o tem instalado com:
      ```bash
      node -v
      ```
    - Se não estiver instalado, baixe e instale a versão recomendada.

2. **Clone o Repositório**:
    - Copie a URL do repositório e execute o comando abaixo no terminal:
      ```bash
      git clone <URL_DO_REPOSITORIO>
      ```

## 🌐 Deploy

Para fazer o deploy do jogo, você pode utilizar plataformas como [GitHub Pages](https://pages.github.com/) ou [Netlify](https://www.netlify.com/). Siga as instruções fornecidas por essas plataformas para deploy de sites estáticos.

1. **GitHub Pages**:
    - Ative o GitHub Pages no repositório do projeto apontando para a branch que contém o `index.html`.

2. **Netlify**:
    - Conecte seu repositório ao Netlify e configure o build para publicar seu site.
