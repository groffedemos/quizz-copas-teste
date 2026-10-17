# Quiz – Copa do Mundo 2022

Quiz em português com 10 perguntas sobre a Copa do Mundo de futebol masculino de 2022 (Catar). Cada pergunta tem uma única resposta correta.

## Estrutura

- `index.html`: página única com HTML, CSS (`<style>`) e JavaScript (`<script>`). Sem bibliotecas, fontes externas ou servidor.
- `README.md`: este arquivo.

Dentro do `index.html`, as perguntas ficam no array `questions` (`q` = enunciado, `o` = opções, `a` = índice da resposta correta).

## Como abrir

Dê duplo clique em `index.html` ou abra-o no navegador (por exemplo, `xdg-open index.html`). Não é necessário servidor nem internet.

## Recursos

- Progresso, pontuação e feedback de acerto/erro (com texto e ícones, não só cor).
- Resultado final com botão "Jogar novamente".
- Layout responsivo, foco visível e navegação por teclado (setas/Tab para escolher, Enter para responder).
- Tema claro/escuro: o tema inicial segue a preferência do sistema e o botão no topo alterna entre eles (cores definidas por variáveis CSS em `:root` e `:root[data-theme="dark"]`).
