## Aula 1 - *Hello World*

* Ensinando como fazer um Hello world ser exibido na tela e explicando como funciona o console.log

## Aula 2 - *VERIFICAR*

* Rever para anotar

## Aula 3 - *Tipos de interpretação de texto*

* Ensinando a diferenciar tipos de texto e números dentro de uma frase

## Aula 4 - *Comentários*

* Inserindo comentários em uma linha utilizando //
* Inserindo comentários em múltiplas linhas utilizando */ 
* Selecionando e comentando múltiplas linhas com o comando CTRL + ;

## Aula 5 - *Introdução sobre HTML*

* Exibindo um arquivo JavaScript dentro de uma página HTML, apontando pelo **script src='caminho do script'></script**

## Aula 6 - *Introdução sobre variáveis*

* Não podemos criar variáveis com palavras reservadas
* Variáveis precisam ter nomes significativos
* Não pode começar o nome de uma variável com um número
* Nomes de variáveis não podem conter espaços ou traços
* Utilizamos camelCase *Maiúsculas ou minúsculas*
* Case-sensitive
* **NÃO UTILIZE VAR, UTILIZE LET!**

## Aula 7 - *Constantes*

* Não podemos criar constantes com palavras reservadas
* Constantes precisam ter nomes significativos
* Não pode começar o nome de uma variável com um número
* Nomes de variáveis nao podem conter espaços ou traços
* Utilizamos camelCase
* Case-sensitive
* Não pode modificar o valor de uma constante
* **NÃO UTILIZE VAR, UTILIZE CONST!**

## Aula 8 - *Exercício de constantes*

* Cálculo de IMC 

## Aula 9 - *Dados primitivos*

* Dados primitivos: String, number, undefined, null, boolean, symbol

## Aula 10 - *Aritméticos*

* ( + ) Adição / Concatenação
* ( - ) Subtração
* ( / ) Divisão
* ( * ) Multiplicação
* ( ** ) Potenciação
* ( % ) Resto da divisão
* contador++; // ++ = operador de incremento | -- = decremento
* NaN - not a number | paserInt (Inteiro) | parseFloat (decimas) | Number ()

## Aula 11 - *Exercício de cálculo com HTML E JS*

* Página web para adicionar dois números e exibia o resultado da soma

## Aula 12 - *Mudando variáveis*

* Exercicio para mudar a posição de algumas variáveis copiando o valor de outras

## Aula 13 - *Exercício criando HTML que fala informações sobre o nome*

* Exibe informações utilizando o nome que foi digitado no prompt

## Aula 14 - *Casas decimais e números*

* Padrão que o JS segue para casas decimais

console.log(num1.toString() + num2) -> Concatena
console.log(num1.toString(2)); -> Transforma pra binário
console.log(num1.toFixed(2)); -> Reduz casa decimal
console.log(Number.isInteger(num1)); -> se o numero é inteiro ou não
let temp = num1 * '5';
console.log(Number.isNaN(temp)); -> Se é um número

## Aula 15 - *Arredondamento*

*console.log(100 / 0);* cuidado pois as contas são infinitas e constam como verdadeiras
let num2 = Math.floor(num1); *Arredonda p baixo*
let num2 = Math.ceil(num1); *Arredonda p cima*
let num2 = Math.round(num1); *Arredonda conforme as casas maiores ou menores*
console.log(Math.max(1,2,3,4,5,-10,-50,1500,9,8,7,6)); *maior numero da sequencia*
console.log(Math.max(1,2,3,4,5,-10,-50,1500,9,8,7,6)); *menor numero da sequencia*
const aleatorio = Math.round(Math.random() * (10 - 5) +5); *gera numero aleatorio arredondado*
console.log(Math.pow(2, 10)); *potenciacao*

## Aula 16 - *Introdução a Array*

* Criando uma constante com um nome X e adicionando um array const alunos = ['Luiz', 'Leonardo', 'Maria'];
* alunos[0] = 'Eduardo'; // *Altera*
* alunos[3] = 'Luiza'; // *Adiciona*
* console.log(alunos[0]); // *Visualiza pos 0*
* console.log(alunos); // *Visualiza tudo*
* alunos[alunos.length] = 'Luiza'; // *Adiciona no final sem saber o tamanho*
* alunos[alunos.length] = 'Fabio';
* alunos[alunos.length] = 'Luana';
* alunos.push('Otavio'); // *Adiciona no fim*
* alunos.unshift('Luiza'); // *Adiciona no começo*
* const removido = alunos.pop(); // *Remove do final*
* const removido = alunos.shift(); // *Remove do começo*
* delete alunos[1]; // *Deleta do índice e deixa espaço*
* console.log(alunos.slice(0, -2)); // *Seleciona um grupo dentro do array*

## Aula 17 - *Arrow functions*

* Explicando a diferença entre utilizar uma arrow function ou function normal

* const raiz = n => n ** 0.5;

* const raiz = function (n) {
    return n ** 0.5;
};

* As duas anteriores funcionam da mesma maneira, porém uma mais resumida e mais bonita.

## Aula 18 - *VERIFICAR*

## Aula 19 - *Mais sobre variáveis*

* Primitivos são imutáveis (String, number, boolean, undefined, null(bigint, symbol))
* Refêrencia são mutáveis (Array, object, function) todos são passados por referência

let a = [1, 2, 3];
let b = [...a];
let c = b;
console.log(a, b);

a.push(4); // *adiciona no final*
console.log(a, b);

b.pop(); // *remove no final*
console.log(a, b);

a.push('Leonardo');
console.log(c);
*/

## Aula 20 - *Query selector em HTML*

* Utilizando um script JS para criar uma página que solicita nome, sobrenome, peso e altura

* Análisando a saída deste formulário com o console.log