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
    var valor; //  é indefinido 
    valor = 5; // é um número 
    valor = "John"; // é uma string 
    valor = true; // é um valor lógico 
    valor = null; // é indefinido

Classe document
-> Propriedades de Exemplo: – title – Define ou Retorna o Título da Página; – URL – Retorna o URL completo da página;
-> Métodos de Exemplo: – write() – Escreve texto no documento; – writeln() – Escreve uma linha de texto no documento;

02: index02 : Realizar a leitura de dois elementos e mostrar a soma dos mesmos no alerta
https://github.com/mferste/revisaoJavascript/blob/master/index2.html

