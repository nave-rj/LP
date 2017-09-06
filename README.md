# LP-Scripts
Scripts feitos em LP 1003

## Conceitos Bacanas

- html
  Conteúdo do site. Desde textos e imagens até códigos

- javascript
  Linguagem de programação que a gente usa. Com ela é possível executar códigos pelo navegador.

- canvas
  Onde a gente desenha. A tela do pintor.

- context
  O carinha que desenha!

- rectFill
  O DESENHO!
  como usa:
    context.rectFill(posicaoX, posicaoY, largura, altura);
  Lembrando que a posição (0,0) começa no canto *superior esquerdo* da tela.

- fillStyle
  A cor do desenho
  como usa:
    context.fillStyle = "#ff00ff"
  Lembrando que o fillStyle apenas surte efeitos nos comandos de desenho que vêm *depois* dele.

- variável
  Uma _caixa_ onde você pode guardar _valores_
  como usa:
    var nomeDaVariavel = "texto"; // o "var" indica que estamos criando a variável
    var outraVariavel = 42;
    
    context.rectFill( outraVariavel, 0, 50, 50 ); // apenas escrever o nome da variável faz a gente usar seu valor
