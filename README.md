# Mario Jump

## 📒 Descrição
Mario Jump é um jogo de plataforma simples e envolvente, inspirado nos clássicos jogos do Mario. O objetivo do jogo é fazer o Mario pular sobre os tubos que se movem pela tela, evitando colisões. O jogo termina quando o Mario colide com um tubo, exibindo uma imagem de "game over". Este projeto utiliza HTML, CSS e JavaScript para criar uma experiência interativa e divertida.

## 🤖 Tecnologias Utilizadas
- **HTML5:** Estrutura básica do jogo.
- **CSS3:** Estilização e animações.
- **JavaScript:** Lógica de jogo e manipulação de eventos.

## 🧐 Processo de Criação
1. **Estrutura HTML:**
   - Criamos a estrutura básica do jogo utilizando HTML.
   - Adicionamos elementos como o Mario (`mario.gif`), tubos (`pipe.png`) e nuvens (`clouds.png`) dentro de uma `div` principal com a classe `game-board`.

2. **Estilização com CSS:**
   - Definimos o estilo do jogo com CSS, incluindo o plano de fundo, tamanhos e posições dos elementos.
   - Implementamos animações para o movimento dos tubos e das nuvens usando `@keyframes`.
   - Adicionamos uma animação de pulo para o Mario, controlada por uma classe CSS.

3. **Lógica de Jogo em JavaScript:**
   - Selecionamos os elementos HTML relevantes (Mario e tubos) usando `document.querySelector`.
   - Implementamos um evento de teclado (`keydown`) para fazer o Mario pular, adicionando e removendo a classe de pulo (`jump`) com `setTimeout`.
   - Utilizamos um loop (`setInterval`) para verificar continuamente a posição dos tubos e do Mario, detectando colisões e exibindo a imagem de "game over" quando ocorre uma colisão.

## 🚀 Resultados
- **Interface Interativa:** Criamos uma interface de jogo interativa onde o Mario corre continuamente e precisa pular sobre os tubos que se movem da direita para a esquerda.
- **Animações Suaves:** Implementamos animações suaves para o movimento dos tubos e das nuvens, bem como a animação de pulo do Mario.
- **Detecção de Colisão:** Implementamos uma lógica eficaz de detecção de colisão que termina o jogo quando o Mario colide com um tubo, exibindo uma imagem de "game over".
- **Experiência Envolvente:** O jogo oferece uma experiência envolvente, desafiando os jogadores a evitar obstáculos e alcançando uma jogabilidade fluida e divertida.

## 💭 Reflexão (Opcional)
Criar o Mario Jump foi uma jornada divertida e educativa, destacando a simplicidade e eficácia do uso de HTML, CSS e JavaScript para desenvolver jogos interativos. Um dos maiores desafios foi garantir que as animações fossem suaves e que a detecção de colisão funcionasse perfeitamente. Este projeto demonstra como conceitos básicos de desenvolvimento web podem ser aplicados para criar experiências de jogo cativantes. Além disso, explorar o uso de IAs generativas em futuros projetos pode abrir novas possibilidades para conteúdos ainda mais inovadores e imersivos.
