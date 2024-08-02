# JavaScript
## O que é JavaScript?
*JavaScript é uma linguagem de programação de alto nível e dinâmica amplamente utilizada para adicionar interatividade e funcionalidades dinâmicas a páginas web. Desenvolvida inicialmente para execução no navegador, a principal função do JavaScript é permitir a manipulação do DOM (Document Object Model), proporcionando uma maneira de criar e modificar elementos e conteúdos da página de forma dinâmica. Além disso, JavaScript é usado para validar formulários, criar animações, interagir com servidores e muito mais.*

## História e Evolução do JavaScript
**JavaScript foi criado por Brendan Eich em 1995 enquanto trabalhava na Netscape Communications. Originalmente chamado de LiveScript, a linguagem foi renomeada para JavaScript para aproveitar a popularidade da linguagem Java. O JavaScript foi incluído na primeira versão do Netscape Navigator.**

## A evolução do JavaScript inclui várias atualizações importantes:

* 1997: ECMAScript 1.0 - Primeira versão padronizada da linguagem.
* 1999: ECMAScript 3.0 - Introduziu expressões regulares, manipulação de strings e melhorias em arrays e objetos.
* 2005: AJAX - Popularizou a programação assíncrona e a atualização dinâmica de conteúdo web.
* 2009: ECMAScript 5.0 - Adicionou o modo estrito, novos métodos para arrays e objetos, e suporte para JSON.
* 2015: ECMAScript 6 (ES6) - Introduziu grandes melhorias, como classes, módulos, arrow functions, e promessas.
* 2016 em diante: ECMAScript 2016+ - Continuou a adicionar recursos anuais, como o operador de exponenciação, novos métodos para strings e arrays, e melhorias no suporte a assincronismo.

# Características Básicas do JavaScript
__Variáveis:__
Variáveis são usadas para armazenar valores. Em JavaScript, você pode declarar variáveis usando var, let e const:

**var:** Tem escopo de função e pode ser reatribuída.
**let:** Tem escopo de bloco e pode ser reatribuída.
**const:** Tem escopo de bloco e não pode ser reatribuída depois de sua inicialização.
Exemplo:
* let nome = "Ana";
* const idade = 30;

## Tipos de Dados:
JavaScript possui vários tipos de dados, incluindo:

* Número: Representa tanto inteiros quanto números de ponto flutuante.
*let idade = 25;*
*let altura = 1.75;*

## String: Cadeias de caracteres

*let nome = "Carlos";*

## Booleano: Valores true ou false.


*let isOnline = true;*
*Array: Lista ordenada de valores.*



__let frutas = ["maçã", "banana", "laranja"];__
*Objeto: Estruturas de dados que contêm pares chave-valor.*


let pessoa = {
  nome: "Maria",
  idade: 28
};

## Funções:
Funções são blocos de código que realizam uma tarefa específica. Podem ser declaradas de várias formas:

**Declaração de Função:**


function saudacao(nome) {
  return "Olá, " + nome;
}
Expressão de Função:


const saudacao = function(nome) {
  return "Olá, " + nome;
};
Função Arrow:


**const saudacao = (nome) => "Olá, " + nome;**

## JavaScript no Navegador
*Interação com HTML e CSS:*
JavaScript pode acessar e manipular elementos HTML e CSS, permitindo a atualização do conteúdo e estilos da página em resposta a eventos ou mudanças de estado.

Exemplo de manipulação de estilo:


document.getElementById("meuElemento").style.color = "blue";
DOM (Document Object Model):
O DOM é uma representação estruturada do documento HTML que organiza a página em uma árvore de nós. JavaScript utiliza o DOM para acessar e modificar o conteúdo e a estrutura da página.

Exemplo de manipulação de DOM:

let elemento = document.getElementById("meuElemento");
elemento.innerHTML = "Novo conteúdo";

## Ferramentas e Ambiente de Desenvolvimento
Navegadores:

**Google Chrome: Inclui as DevTools, que oferecem ferramentas de depuração e inspeção.**
**Firefox: Oferece as ferramentas de desenvolvedor com funcionalidades similares às do Chrome.**
**Microsoft Edge: Também possui ferramentas de desenvolvedor para depuração.**
Editores de Código:

##Visual Studio Code (VS Code): 
* Editor de código poderoso com suporte a extensões para JavaScript.
* Sublime Text: Editor leve e altamente configurável.
* Atom: Editor de texto desenvolvido pelo GitHub com uma rica seleção de pacotes.
##Ambientes de Desenvolvimento:

* Node.js: Permite a execução de JavaScript fora do navegador, ideal para desenvolvimento de servidores e aplicações de linha de comando.
* Recursos de Aprendizado
* MDN Web Docs: MDN Web Docs - Documentação abrangente e tutoriais.
* JavaScript.info: JavaScript.info - Guia detalhado e tutorial de JavaScript.
* FreeCodeCamp: FreeCodeCamp - Cursos e desafios interativos gratuitos.
* Codecademy: Codecademy - Cursos interativos sobre JavaScript.
* Coursera: Coursera - Cursos online oferecidos por instituições renomadas.
