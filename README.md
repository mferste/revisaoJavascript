Lista de exercícios para revisão geral de javascript:

00:index: Olá mundo, para variar, mais do mesmo para iniciar.
Criar um arquivo HTML5 no vscode chamado index.html então gerar um alerta (alert) com o texto olá mundo na seção body do arquivo usando javascript (script).
Dica: ctrl + barra de espaço trará na versão do vscode ^1.4.1 um snippet para uma página com tudo o que precisamos.
(https://github.com/mferste/revisaoJavascript/blob/master/index.html)
Para inserir códigos JavaScript, iremos fazê-lo em uma Tag HTML apropriada: – <script> – </script> • O JavaScript é orientado a objetos;
– Primeira Classe: document

<script src="meuScript.js"></script>
<script> document.write("Hello World!"); </script>

01:index01: Utilizando um script externo.
Criar novo html, agora index01.html
Ao criar avaliar o uso de main.js, já existente no template.
então criar um arquivo main.js e colocar o alert no mesmo.
(execução de javascript depende da inserção no html, avaliar alterações e observar a criação do html e aparição do alert)
https://github.com/mferste/revisaoJavascript/blob/master/index1.html

Os principais padrões a destacar são:
-> A Linguagem Núcleo: • ECMAScript (Versão 7, de Junho de 2016); • Padrão mantido por ECMA InternationalAssociação Industrial de padronização de tecnologias da Informação e Comunicação;
-> DOM: • Document Object Model; • Define a Interface da Linguagem com o Browser; • Padrão mantido por W3C;

JavaScript é uma linguagem de tipagem dinâmica e fraca:
–> Não é necessário declarar o tipo de uma variável;
–> Todas as variáveis são objetos (referência); – Números são todos reais de 64bits;
–> A variável irá “alterar” o seu tipo de dado conforme os valores forem atribuídos:
-> Tipo de dado dinâmico:
var valor; // é indefinido
valor = 5; // é um número
valor = "John"; // é uma string
valor = true; // é um valor lógico
valor = null; // é indefinido

Classe document
-> Propriedades de Exemplo: – title – Define ou Retorna o Título da Página; – URL – Retorna o URL completo da página;
-> Métodos de Exemplo: – write() – Escreve texto no documento; – writeln() – Escreve uma linha de texto no documento;

02: index02 : Realizar a leitura de dois elementos e mostrar a soma dos mesmos no alerta
https://github.com/mferste/revisaoJavascript/blob/master/index2.html
03: index03 : Que tal inserir novos botões para realizar Multiplicação, subtração e divisão ?

04: index04 : Testar variações...crie um htm com script para testar os itens abaixo, insira comentário para dizer o que fazem:
a)
console.log(document.URL);
b)
filename = "system.php"
console.log(filename.split('.').pop());
filename = "abc.js"
console.log(filename.split('.').pop());

Arrays
Arrays são construídos através de um construtor e possuem tamanho dinâmico:
var nomes = new Array(); //var nomes = [];
nomes[0] = "Fulano de Tal";
nomes[1] = "Beutrano";
nomes.push("Ciclano");

05: index5 : Criar um programa que mostra a inserção de itens em um array, com entrada de valor, botão para inserir e botão para mostrar o array.
https://github.com/mferste/revisaoJavascript/blob/master/index5.html

06: index6 : Altere para somar todos os valores do array e também para fazer a multiplicação de todos os valores do array:
Coloque mais um botão para mostrar esta operação partindo do exemplo 05.

const array = [1, 2, 3, 4, 5, 6];
let s = 0;
let p = 1;
let i;
for (i = 0; i < array.length; i += 1)
{
s += array[i];
p \*= array[i];
}
console.log('Sum : ${s} Product :  ${p}');

07: index7 :
Avaliar o site: http://www.constletvar.com/

Links Externos:
https://www.w3resource.com/javascript-exercises/
https://github.com/gabrieldarezzo/helpjs-ravi#exemplos
