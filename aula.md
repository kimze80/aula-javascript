## Introdução a programação e a Lógica

### O que é um algoritmo

### Receita de bolo?

### Níveis de Abstração

  Linguagem de BAIXO NIVEL (detalhado)
  Linguagem de ALTO NIVEL (simples)


### Compilação x Interpretação

### JAVASCRIPT

### Tipos e Operações

| TIPO    | DESCRIÇÃO  |
| --------|----------- |
| number  | valores numéricos, inteiro ou decimal |
| string  | texto |
| boolean | verdadeiro ou falso|
| object  | armazena diversos valores organizados em pares de chave e valor|
| *array  | armazena diversos valores organizados por posição|

#### Criando arquivos .js

<script src="myscripts.js"></script>

### Conversão de valores
  Soma de numero + string
 
let idadeString = prompt('Digite sua idade'); //o usuário digitou 11 no popup
let idade = Number(idadeString); //converte a string em number

let idadeRelativa = idade + 20;

alert(idadeRelativa); //o resultado é 31

### Condicionais

#### Operadores Lógicos
Toda operação lógica resulta em um valor booleano, ou seja, `true` ou `false`;
| Operador | Descrição |
|----------|---------- |
| == | igual |
| != | diferente |
| ! | negação |
| > | maior |
| < | menor |
| >= | maior ou igual |
| <= | menor ou igual |

## Javascript - DOM
  ### Manipulando o DOM com Javascript
  **querySelector**
  

### Eventos do browser

| Evento | Descrição |
| ------ | --------- |
| onclick | clique do mouse |
| onmouseenter | quando o ponteiro entra no elemento |
| onmousemove | quando o ponteiro se movimenta dentro do elemento |
| onmouseleave | quando o ponteiro sai do elemento |
| onkeydown | quando o elemento tem foco e alguma tecla é pressionada|
| onkeydown | o elemento tem foco e quando alguma tecla é solta após ser pressionada |

### click 

var el = document.getElementById('module')
    clickerFn = function() {
    console.log('Click just happened');
}

el.addEventListener('click', clickerFn);

### show element

#myDIV {
    width: 100%;
    padding: 50px 0;
    text-align: center;
    background-color: lightblue;
    margin-top: 20px;
}

function myFunction() {
    var x = document.getElementById("myDIV");
    if (x.style.display === "none") {
        x.style.display = "block";
    } else {
        x.style.display = "none";
    }
}

# ALMOÇO

## Aplicativos Mobile

  ### Opção 1: Aplicativos Nativos
  **Vantagens:** maior performance e flexibilidade de uso de recursos plataforma.
  **Desvantagens:** maior custo e tempo de desenvolvimento, manutenção de duas bases de código.
  
  ### Opção 2: Aplicativos Nativos com base de código compartilhada
  **Vantagens:** maior agilidade no desenvolvimento e alteração de apps
  **Desvantagens:** menor flexibilidade para uso de recursos nativos, ainda é necessário fazer ajustes específicos por plataforma
  
  ### Opção 3: Aplicativos Híbridos
  **Vantagens:** é uma das formas mais rápidas e baratas para desenvolvimento de apps, um programador web pode reutilizar seus conhecimentos de HTML, CSS e JS
  **Desvantagens:** menor performance e maior quantidade de limitações em relação a apps puramente nativos
  
  ### Opção 4: PWA (Progressive Web Apps)
  **Vantagens:** é uma das formas mais rápidas e baratas para desenvolvimento de apps, um programador web pode reutilizar seus conhecimentos de HTML, CSS e JS
  **Desvantagens:** menor performance e maior quantidade de limitações em relação a apps puramente nativos
