# Módulo 04 - CSS - Cascade Style Sheets

## O que é?

- Folha de Estilo em Cascatas;  
- Define os estilos de uma página HTML.


## Seletores mais avançados

- * (asterísco): vai aplicar os estilos em todos os elementos do documento HTML;  
- descendência: qualquer elemento F que seja um descendente (esteja “dentro”) de um elemento E `li a {  }`; 
- filho (>): `li > a {  }`;  
- adjacente (h1 + h4): vou aplicar os elementos em que todo `h4` que venha logo após o `h1`;  
- atributo: `a[href]='/recibo'` > vai aplicar em todos os links que tenham como `href='/recibo'`;  
- pseudo-classes: casam elementos baseadas em características outras que não; seu nome, seus atributos ou seu conteúdo, como por exemplo `:first-child`, `:link` e `:visited`;  
- pseudo-elementos: permitem acessar e formatar partes do documento que não estão disponíveis como nós da árvore do documento, como por exemplo `:first-line`, `:first-letter`, `:before` e `:after`.


## Posicionamento de elementos

### `box-model`

O HTML trata todos os elementos como uma box model (textos, imagens, etc) `margin > border > padding > content`.


