# Módulo 06 - Javascript

## O que é o Javascript ?
Nasceu em 1995, criada por Brendan Eich, na Netscape. Surgiu para deixar as páginas HTML mais dinâmicas, já que na época, apenas HTML e CSS não era possível ter dinamismo, ou seja, as páginas eram estáticas.

O Javascript possui múltiplos paradigmas, sendo eles:
- Orientado à objetos;
- Funcional;
- Orientada à eventos.

Além disso, ela possui tipagem dinâmica e fraca.


## Evolução do Javascript
- Normalizado em 1996 através da ECMA International;
- Nome oficial da linguagém é ECMAScript;
- A versão atual é o ES8 (versão 8) (maio-2021);
- Não é utilizada apenas no front-end, onde, após a criação do NodeJS é possível utilizar o JS de ponta a ponta, no front ou back.


## Primeiros passos
### Tipos primitivos

São a base de um código, ou seja, são os elementos mais básicos de uma linguagem de programação. 

Onde utilizamos para representarmos algum dado bruto. Assim, com estes tipos que somos capazes de construir projetos com estruturas mais complexas.

Atualmente, o JS possui os seguintes tipos primitovos: string, number, boolean, null, undefined, symbol, object (todo o resto, incluindo arrays e datas).

#### `string`
- Tipo texto.

#### `number`
- Todos os números, sejam inteiros ou decimais, positivos ou negativos.

#### `boolean`
- É um dado lógico, verdadeiro ou falso (*true* ou *false*).

#### `null`
- É um valor nulo, inexistente.

#### `undefined`
- É um valor indefinido. Quando o JS não consegue definir um tipo sob um determinado dado.

#### `symbol`
- Introduzido no JS no ES6;  
- Onde valores desse tipo podem ser usados para fazer propriedades de objetos anônimos;  
- Ele pode ser usado como chave de uma propriedade de objeto quando este tem a intenção de ser privada, para uso interno da classe ou do tipo do objeto em questão.


### Operações Básicas
#### Operadores aritméticos
- Adição;  
- Subtração;  
- Multiplicação;  
- Divisão;  
- Restante (%).

#### Operadores de incremento e decremento
- Incremento (++);  
- Decremento (--).

#### Operadores de atribuição
- Adição (+=);  
- Subtração (-=);  
- Multiplicação (*=);  
- Divisão (/=).


### Recursos nativos do browser
- `console.log('hello world!')`;  
- `console.info('informações de registro!')`;  
- `console.error('algum erro!')`;  
- `console.warn('hello world!')`;  
- `alert('mensagem na tela')`;  
- `confirm('deseja confirmar isso?')`;  
- `prompt('qual seu nome?')`: exibe a mensagem como se fosse um `alert`, incluindo um campo do tipo `input` para digitarmos algum dado.


### Declarando variáveis
São recursos que utilizamos para armezarmos valores dentro do nosso código.

A partir do ES6, temos 3 tipos de variáveis: `var`, `let` e `const`.

#### `var`
- vem desde as versões mais antigas do JS;  
- declara uma variável, opcionalmente, inicializando-a com um valor;  
- hoisting?

#### `let`
- variável local de escopo de bloco;  
- leva em conta o escopo de cada bloco de código;  
- opcionalmente, inicializando-a com um valor.

#### `const`
- constante de escopo de bloco, apenas leitura.


## Condicionais
### Comparações de dados
Basicamente são operações onde o retorno será do tipo *booleano*, ou seja, vai retornar *true* ou *false*. Sempre vai retornar valores lógicos.  

Os operadores de comparação são:  
- Igualdade, não identifica o tipo e sim apenas o valor do dado (==);  
- Igualdade estrita, ou seja, identifica se os valores são iguais em tipo e valor (===);  
- Não igualdade estrita (!==);  
- Menor que (<);  
- Maior que (>);  
- Menor ou igual que (<=);  
- Maior ou igual que (>=).


### Operações lógicas
As operações lógicas são expressões construídas a partir de operações com valores booleanos.
#### AND
#### OR
#### NOT

### Operações condicionais
#### IF
#### IF.. ELSE
#### IF.. ELSE IF..

#### Operador ternário
##### `(velocity > 100) ? console.log('vdd') : console.log('falso')`

### Switch
- Avalia uma expressão;  
- Estrutura de controle de fluxo;  
- Procura uma melhor caso (`case`) que atende ao resultado.

## Loops (Estruturas de repetição)
São utilizadas para repetir um bloco de código. Pode ser um determinado número de vezes ou até uma determinada condição seja atendida.

### While
A declaração while cria um laço que executa uma rotina especifica enquanto a condição de teste for avaliada como verdadeira. A condição é avaliada antes da execução da rotina. Ele recebe apenas uma expressão.

```
let velocity = 60
let acceleration = 6

while (velocity <= 100>) {
  console.log('Estamos em ' + velocity + 'km/s')
  velocity += acceleration
}
```

### For
A instrução for cria um loop que consiste em três expressões opcionais, dentro de parênteses e separadas por ponto e vírgula, seguidas por uma declaração ou uma sequência de declarações executadas em sequência.

Ao contrário do `while`, com o `for` é possível adicionarmos a variável que utilizaremos para controlar as iterações.

```
for (<variável>; <expressão>; <ação de controle>) {
  <bloco de código>
}
```

Por exemplo:
```
let people = "Holdor"

for (let i = 0; i < people.length; i++) {
  console.log(people[i])
}
```

### Do...while
A declaração `do...while` cria um laço que executa uma declaração até que o teste da condição for falsa (`false`). A condição é avaliada depois que o bloco de código é executado, resultando que uma declaração seja executada pelo menos uma vez.

```
let velocity = 60
let acceleration = 6

do {
  console.log('Estamos em ' + velocity + 'km/s')
  velocity += acceleration
} while (velocity <= 100)
```


## Funções
## Arrays
## Objetos
## Classes - POO
## Manipulando o DOM
## Eventos


## Referências

- [Primitivo](https://developer.mozilla.org/pt-BR/docs/Glossary/Primitive)  
- [A quick tour of JavaScript primitives](https://milkjar.medium.com/a-quick-tour-of-javascript-primitives-894eceee31c2#:~:text=Primitives%20are%20the%20simplest%20elements,which%20can%20not%20be%20changed.)  
- [Matemática básica no JavaScript — números e operadores](https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/First_steps/Math#operadores_aritm%C3%A9ticos)  
- [Console](https://developer.mozilla.org/pt-BR/docs/Web/API/Console)  
- [While](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/while)  
- [For](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/for)
- [Do...while](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/do...while)