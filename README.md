# RxJS

O **Angular** é um _framework_ que permite construir aplicações profissionais e robustas. Parte desse poder vem das ferramentas e bibliotecas que o compõe. E uma das mais poderosas e versáteis é o **RxJS**.

## 01 - Obervables <br/> 
  - Quando queremos apenas um valor e de forma imperativa, isso é, recebemos assim que evocamos uma ação, o que utilizamos? Uma ***Função***!
  - Quando não queremos apenas um valor, mas sim, iterar sobre uma coleção de valores, o que podemos utilizar? Um ***Iterator***.
  - Quando o valor que recebemos não pode ser recebido de imediato, ou seja, para obter essa informação, precisamos esperar uma requisição. Nessa situação, quando temos    que receber um único valor, o que utilizamos? Uma ****Promise****.
  - Se precisamos iterar sobre uma coleção, mas, precisamos fazer essa ação de forma reativa, o que utilizaremos? Aí, entra o ***OBSERVABLE***.<br/>
   
## 02 - Operadores de transformação<br/>
  - *Pipe*: para manipular o fluxo de informação usamos o método pipe, com ele nós podemos vincular os operadores, incluindo combinar vários operadores e ter apenas um         retorno. Ex: .pipe()
  - *Operador Map*: quando precisamos mudar o objeto que o fluxo retorna, como por exemplo um array de ações para um array de ações ordenado. Ela recebe como parâmetro       uma função, Então, o map vai receber uma função, que recebe como parâmetro o dado, o objeto que vem do fluxo, e espera como retorno um novo objeto, que no nosso caso     é o mesmo array de Ações, porém, ordenado. Ex: .pipe(map())
  - *Tap*: ele também vai receber uma função e essa função, ela tem como parâmetro o (valor) que está sendo enviado, ao contrario do operador map o tap não altera    o         objeto, o fluxo.
  - *Pluck*: Essa operação de extrair um atributo de um objeto, para se trabalhar com ele, é tão comum que a equipe do RxJS criou um operador só para isso, o pluck. Esse       operador não recebe uma função, ele recebe uma string, que é o nome da propriedade que eu quero extrair do objeto que eu estou recebendo.
  - *Unsubscribe*:
  - *Async pipe*:

