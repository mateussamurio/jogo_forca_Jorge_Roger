# JOGO DA FORCA;
O jogo da forca é um jogo em que o jogador tem que acertar qual é a palavra proposta, tendo como dica o número de letras e o tema ligado à palavra. A cada letra errada, é desenhado uma parte do corpo do enforcado.

Projeto desenvolvido por Jorge Mateus e Roger Michel.

# Vídeos Utilizados;

[1º Vídeo, "Jogo da Forca - HTML, CSS e JS Puro!"](https://www.youtube.com/watch?v=KNH_-_esmaI)

[2º Vídeo, "Jogo da Forca - HTML + JS"](https://www.youtube.com/watch?v=F-4zVtms5es)

# Descrição do Jogo;

O jogo foi desenvolvido com base nos vídeos acima, com a utilização das linguagens HTML, CSS e JavaScript.

A princípio, o objetivo inicial envolvia construir um código simples, porém funcional.

No HTML, o foco principal foi construir o design da forca, de acordo com as seguintes linhas:
```
<svg height="250" width="200" class="forca">
          <!-- forca -->
          
          <line x1="60" y1="20" x2="140" y2="20" />
          <line x1="140" y1="20" x2="140" y2="50" />
          <line x1="60" y1="20" x2="60" y2="230" />
          <line x1="20" y1="230" x2="100" y2="230" />

          <!-- cabeça -->
          <circle cx="140" cy="70" r="20" class="forca-parte" />
          <!-- corpo -->
          <line x1="140" y1="90" x2="140" y2="150" class="forca-parte" />
          <!-- braços -->
          <line x1="140" y1="120" x2="120" y2="100" class="forca-parte" />
          <line x1="140" y1="120" x2="160" y2="100" class="forca-parte" />
          <!-- pernas -->
          <line x1="140" y1="150" x2="120" y2="180" class="forca-parte" />
          <line x1="140" y1="150" x2="160" y2="180" class="forca-parte" />
        </svg>
```
Nas quais foram construídos o instrumento e o boneco, respectivamente.

Além disso, no CSS, foram utilizadas algumas propriedades (de espaços, cores, entre outros), com o intuito de desenvolver uma interface estética simples.

Por fim, no JavaScript, foram criadas as principais funções do jogo, a fim de trazer funcionalidade ao jogo.

Como, por exemplo, a função "AtualizarJogo", que contém em si outras 5 funções essenciais:
```
function atualizarJogo() {
  mostrarLetrasErradas();
  mostrarLetrasCertas();
  desenharForca();
  checarJogo();
  revelarPalavra();
}
```

# Imagens;

| ID | Primeira Tela | Segunda Tela | Terceira Tela |
|----|---------------|--------------|---------------|
| 1  |   Início      |   Ao jogar   |   Resultados  |
| 2  | ![image](https://user-images.githubusercontent.com/100212322/162653004-715751dc-a60b-4dc6-810f-bba006ccc6e8.png) | ![image](https://user-images.githubusercontent.com/100212322/162653142-251f03bf-91b9-46f6-b4d8-a474f6abdfd4.png) | ![image](https://user-images.githubusercontent.com/100212322/162653195-6a8c68c9-54eb-4685-871a-c6aafc21e622.png) |
 
# Alterações e Atualizações;

1. Cor de fundo;
2. Alterações de nomes de variáveis e funções;
3. Espaçamento aumentado;
4. Tamanho das fontes;
5. Tipos das fontes;
6. Centralizamos o jogo;
7. Tamanho dos botões;
8. Adicionamos um rodapé e um título;
9. Alteramos os textos;
10. Adicionamos 50+ palavras;
11. Adicionamos um método que mostra qual era a palavra certa;
12. Adicionamos uma imagem ao perder;

# Tecnologias e Ferramentas Utilizadas;
- **HTML**: estrutura do jogo
- _CSS_: estilo do jogo
- *_JS_* funções do jogo
