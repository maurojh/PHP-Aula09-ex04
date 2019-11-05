<?xml version="1.0" encoding="utf-8"?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="en" xml:lang="en">
<head>
<!-- 2019-11-05 ter 19:00 -->
<meta http-equiv="Content-Type" content="text/html;charset=utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>&lrm;</title>
<meta name="generator" content="Org mode" />
<style type="text/css">
 <!--/*--><![CDATA[/*><!--*/
  .title  { text-align: center;
             margin-bottom: .2em; }
  .subtitle { text-align: center;
              font-size: medium;
              font-weight: bold;
              margin-top:0; }
  .todo   { font-family: monospace; color: red; }
  .done   { font-family: monospace; color: green; }
  .priority { font-family: monospace; color: orange; }
  .tag    { background-color: #eee; font-family: monospace;
            padding: 2px; font-size: 80%; font-weight: normal; }
  .timestamp { color: #bebebe; }
  .timestamp-kwd { color: #5f9ea0; }
  .org-right  { margin-left: auto; margin-right: 0px;  text-align: right; }
  .org-left   { margin-left: 0px;  margin-right: auto; text-align: left; }
  .org-center { margin-left: auto; margin-right: auto; text-align: center; }
  .underline { text-decoration: underline; }
  #postamble p, #preamble p { font-size: 90%; margin: .2em; }
  p.verse { margin-left: 3%; }
  pre {
    border: 1px solid #ccc;
    box-shadow: 3px 3px 3px #eee;
    padding: 8pt;
    font-family: monospace;
    overflow: auto;
    margin: 1.2em;
  }
  pre.src {
    position: relative;
    overflow: visible;
    padding-top: 1.2em;
  }
  pre.src:before {
    display: none;
    position: absolute;
    background-color: white;
    top: -10px;
    right: 10px;
    padding: 3px;
    border: 1px solid black;
  }
  pre.src:hover:before { display: inline;}
  /* Languages per Org manual */
  pre.src-asymptote:before { content: 'Asymptote'; }
  pre.src-awk:before { content: 'Awk'; }
  pre.src-C:before { content: 'C'; }
  /* pre.src-C++ doesn't work in CSS */
  pre.src-clojure:before { content: 'Clojure'; }
  pre.src-css:before { content: 'CSS'; }
  pre.src-D:before { content: 'D'; }
  pre.src-ditaa:before { content: 'ditaa'; }
  pre.src-dot:before { content: 'Graphviz'; }
  pre.src-calc:before { content: 'Emacs Calc'; }
  pre.src-emacs-lisp:before { content: 'Emacs Lisp'; }
  pre.src-fortran:before { content: 'Fortran'; }
  pre.src-gnuplot:before { content: 'gnuplot'; }
  pre.src-haskell:before { content: 'Haskell'; }
  pre.src-hledger:before { content: 'hledger'; }
  pre.src-java:before { content: 'Java'; }
  pre.src-js:before { content: 'Javascript'; }
  pre.src-latex:before { content: 'LaTeX'; }
  pre.src-ledger:before { content: 'Ledger'; }
  pre.src-lisp:before { content: 'Lisp'; }
  pre.src-lilypond:before { content: 'Lilypond'; }
  pre.src-lua:before { content: 'Lua'; }
  pre.src-matlab:before { content: 'MATLAB'; }
  pre.src-mscgen:before { content: 'Mscgen'; }
  pre.src-ocaml:before { content: 'Objective Caml'; }
  pre.src-octave:before { content: 'Octave'; }
  pre.src-org:before { content: 'Org mode'; }
  pre.src-oz:before { content: 'OZ'; }
  pre.src-plantuml:before { content: 'Plantuml'; }
  pre.src-processing:before { content: 'Processing.js'; }
  pre.src-python:before { content: 'Python'; }
  pre.src-R:before { content: 'R'; }
  pre.src-ruby:before { content: 'Ruby'; }
  pre.src-sass:before { content: 'Sass'; }
  pre.src-scheme:before { content: 'Scheme'; }
  pre.src-screen:before { content: 'Gnu Screen'; }
  pre.src-sed:before { content: 'Sed'; }
  pre.src-sh:before { content: 'shell'; }
  pre.src-sql:before { content: 'SQL'; }
  pre.src-sqlite:before { content: 'SQLite'; }
  /* additional languages in org.el's org-babel-load-languages alist */
  pre.src-forth:before { content: 'Forth'; }
  pre.src-io:before { content: 'IO'; }
  pre.src-J:before { content: 'J'; }
  pre.src-makefile:before { content: 'Makefile'; }
  pre.src-maxima:before { content: 'Maxima'; }
  pre.src-perl:before { content: 'Perl'; }
  pre.src-picolisp:before { content: 'Pico Lisp'; }
  pre.src-scala:before { content: 'Scala'; }
  pre.src-shell:before { content: 'Shell Script'; }
  pre.src-ebnf2ps:before { content: 'ebfn2ps'; }
  /* additional language identifiers per "defun org-babel-execute"
       in ob-*.el */
  pre.src-cpp:before  { content: 'C++'; }
  pre.src-abc:before  { content: 'ABC'; }
  pre.src-coq:before  { content: 'Coq'; }
  pre.src-groovy:before  { content: 'Groovy'; }
  /* additional language identifiers from org-babel-shell-names in
     ob-shell.el: ob-shell is the only babel language using a lambda to put
     the execution function name together. */
  pre.src-bash:before  { content: 'bash'; }
  pre.src-csh:before  { content: 'csh'; }
  pre.src-ash:before  { content: 'ash'; }
  pre.src-dash:before  { content: 'dash'; }
  pre.src-ksh:before  { content: 'ksh'; }
  pre.src-mksh:before  { content: 'mksh'; }
  pre.src-posh:before  { content: 'posh'; }
  /* Additional Emacs modes also supported by the LaTeX listings package */
  pre.src-ada:before { content: 'Ada'; }
  pre.src-asm:before { content: 'Assembler'; }
  pre.src-caml:before { content: 'Caml'; }
  pre.src-delphi:before { content: 'Delphi'; }
  pre.src-html:before { content: 'HTML'; }
  pre.src-idl:before { content: 'IDL'; }
  pre.src-mercury:before { content: 'Mercury'; }
  pre.src-metapost:before { content: 'MetaPost'; }
  pre.src-modula-2:before { content: 'Modula-2'; }
  pre.src-pascal:before { content: 'Pascal'; }
  pre.src-ps:before { content: 'PostScript'; }
  pre.src-prolog:before { content: 'Prolog'; }
  pre.src-simula:before { content: 'Simula'; }
  pre.src-tcl:before { content: 'tcl'; }
  pre.src-tex:before { content: 'TeX'; }
  pre.src-plain-tex:before { content: 'Plain TeX'; }
  pre.src-verilog:before { content: 'Verilog'; }
  pre.src-vhdl:before { content: 'VHDL'; }
  pre.src-xml:before { content: 'XML'; }
  pre.src-nxml:before { content: 'XML'; }
  /* add a generic configuration mode; LaTeX export needs an additional
     (add-to-list 'org-latex-listings-langs '(conf " ")) in .emacs */
  pre.src-conf:before { content: 'Configuration File'; }

  table { border-collapse:collapse; }
  caption.t-above { caption-side: top; }
  caption.t-bottom { caption-side: bottom; }
  td, th { vertical-align:top;  }
  th.org-right  { text-align: center;  }
  th.org-left   { text-align: center;   }
  th.org-center { text-align: center; }
  td.org-right  { text-align: right;  }
  td.org-left   { text-align: left;   }
  td.org-center { text-align: center; }
  dt { font-weight: bold; }
  .footpara { display: inline; }
  .footdef  { margin-bottom: 1em; }
  .figure { padding: 1em; }
  .figure p { text-align: center; }
  .inlinetask {
    padding: 10px;
    border: 2px solid gray;
    margin: 10px;
    background: #ffffcc;
  }
  #org-div-home-and-up
   { text-align: right; font-size: 70%; white-space: nowrap; }
  textarea { overflow-x: auto; }
  .linenr { font-size: smaller }
  .code-highlighted { background-color: #ffff00; }
  .org-info-js_info-navigation { border-style: none; }
  #org-info-js_console-label
    { font-size: 10px; font-weight: bold; white-space: nowrap; }
  .org-info-js_search-highlight
    { background-color: #ffff00; color: #000000; font-weight: bold; }
  .org-svg { width: 90%; }
  /*]]>*/-->
</style>
<script type="text/javascript">
/*
@licstart  The following is the entire license notice for the
JavaScript code in this tag.

Copyright (C) 2012-2019 Free Software Foundation, Inc.

The JavaScript code in this tag is free software: you can
redistribute it and/or modify it under the terms of the GNU
General Public License (GNU GPL) as published by the Free Software
Foundation, either version 3 of the License, or (at your option)
any later version.  The code is distributed WITHOUT ANY WARRANTY;
without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE.  See the GNU GPL for more details.

As additional permission under GNU GPL version 3 section 7, you
may distribute non-source (e.g., minimized or compacted) forms of
that code without the copy of the GNU GPL normally required by
section 4, provided you include this license notice and a URL
through which recipients can access the Corresponding Source.


@licend  The above is the entire license notice
for the JavaScript code in this tag.
*/
<!--/*--><![CDATA[/*><!--*/
 function CodeHighlightOn(elem, id)
 {
   var target = document.getElementById(id);
   if(null != target) {
     elem.cacheClassElem = elem.className;
     elem.cacheClassTarget = target.className;
     target.className = "code-highlighted";
     elem.className   = "code-highlighted";
   }
 }
 function CodeHighlightOff(elem, id)
 {
   var target = document.getElementById(id);
   if(elem.cacheClassElem)
     elem.className = elem.cacheClassElem;
   if(elem.cacheClassTarget)
     target.className = elem.cacheClassTarget;
 }
/*]]>*///-->
</script>
</head>
<body>
<div id="content">
<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#orgb5f5e03">1. Usando biblioteca para gerar arquivo PDF</a>
<ul>
<li><a href="#org60bfd3e">1.1. Instalação usando o git</a></li>
<li><a href="#orgfe73388">1.2. Exercício 1</a></li>
<li><a href="#org4a1424b">1.3. Imprimindo tabelas</a></li>
<li><a href="#org1cf26fc">1.4. Exercício 2</a></li>
<li><a href="#org426358a">1.5. Nome do arquivo PDF</a></li>
<li><a href="#orgecb9b1e">1.6. Exercício 3</a></li>
<li><a href="#org5be1725">1.7. Exercício 4</a></li>
</ul>
</li>
</ul>
</div>
</div>
<div id="outline-container-orgb5f5e03" class="outline-2">
<h2 id="orgb5f5e03"><span class="section-number-2">1</span> Usando biblioteca para gerar arquivo PDF</h2>
<div class="outline-text-2" id="text-1">
<p>
Podemos usar <a href="https://github.com/dompdf/dompdf">dompdf</a> para gerar arquivos PDF em PHP.
</p>
</div>

<div id="outline-container-org60bfd3e" class="outline-3">
<h3 id="org60bfd3e"><span class="section-number-3">1.1</span> Instalação usando o git</h3>
<div class="outline-text-3" id="text-1-1">
<p>
Abra o prompt de comando e acesse a pasta onde irá ficar o dompdf:
</p>

<pre class="example">
Microsoft Windows [versão 10.0.18362.295]
(c) 2019 Microsoft Corporation. Todos os direitos reservados.

C:\Users\Aluno&gt;cd C:\wamp64\www\site

C:\wamp64\www\site&gt;
</pre>

<p>
Em seguida execute os seguintes comandos na ordem em que aparecem:
</p>

<pre class="example">
git clone https://github.com/dompdf/dompdf.git
cd dompdf

git clone https://github.com/PhenX/php-font-lib.git lib/php-font-lib
cd lib/php-font-lib
git checkout 0.5.1
cd ..

git clone https://github.com/PhenX/php-svg-lib.git php-svg-lib
cd php-svg-lib
git checkout v0.3
</pre>

<p>
Para testar salve o seguinte documento na pasta do site, no exemplo usei: <code>C:\wamp64\www\site&gt;</code>
</p>

<pre class="example">
&lt;?php

require_once 'dompdf/lib/html5lib/Parser.php';
require_once 'dompdf/lib/php-font-lib/src/FontLib/Autoloader.php';
require_once 'dompdf/lib/php-svg-lib/src/autoload.php';
require_once 'dompdf/src/Autoloader.php';
Dompdf\Autoloader::register();

// Facilitar a referência à Dompdf
use Dompdf\Dompdf;

// cria uma instância e usa a classe dompdf
$dompdf = new Dompdf();
$dompdf-&gt;loadHtml('Instalação concluída com sucesso! Parabéns!');

// (Opcional) Ajusta o tamanho e orientação do papel
// outra opção é 'portrait'
$dompdf-&gt;setPaper('A4', 'landscape');

// Renderiza o HTML como PDF
$dompdf-&gt;render();

// Gera a saída no navegador.
$dompdf-&gt;stream();

?&gt;
</pre>
</div>
</div>

<div id="outline-container-orgfe73388" class="outline-3">
<h3 id="orgfe73388"><span class="section-number-3">1.2</span> Exercício 1</h3>
<div class="outline-text-3" id="text-1-2">
<p>
Crie uma página que gere um arquivo PDF contendo seu nome, a data e hora atual.
</p>
</div>
</div>

<div id="outline-container-org4a1424b" class="outline-3">
<h3 id="org4a1424b"><span class="section-number-3">1.3</span> Imprimindo tabelas</h3>
<div class="outline-text-3" id="text-1-3">
<p>
Você pode carregar elementos HTML usando o método <code>dompdf-&gt;loadHtml()</code>.
</p>

<pre class="example">
&lt;?php

require_once 'dompdf/lib/html5lib/Parser.php';
require_once 'dompdf/lib/php-font-lib/src/FontLib/Autoloader.php';
require_once 'dompdf/lib/php-svg-lib/src/autoload.php';
require_once 'dompdf/src/Autoloader.php';
Dompdf\Autoloader::register();

// reference the Dompdf namespace
use Dompdf\Dompdf;

// instantiate and use the dompdf class
$dompdf = new Dompdf();
$dompdf-&gt;loadHtml('&lt;table border="1"&gt;&lt;tr&gt;&lt;th&gt;Editor&lt;/th&gt;&lt;th&gt;Site&lt;/th&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;Brackets&lt;/td&gt;&lt;td&gt;http://brackets.io/&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;Atom&lt;/td&gt;&lt;td&gt;http://atom.io/&lt;/td&gt;&lt;/tr&gt;&lt;/table&gt;');

// (Optional) Setup the paper size and orientation
$dompdf-&gt;setPaper('A4', 'landscape');

// Render the HTML as PDF
$dompdf-&gt;render();

// Output the generated PDF to Browser
$dompdf-&gt;stream();

?&gt;
</pre>

<p>
Você pode passar uma variável com os elementos para <code>loadHtml()</code>:
</p>

<pre class="example">
&lt;?php

require_once 'dompdf/lib/html5lib/Parser.php';
require_once 'dompdf/lib/php-font-lib/src/FontLib/Autoloader.php';
require_once 'dompdf/lib/php-svg-lib/src/autoload.php';
require_once 'dompdf/src/Autoloader.php';
Dompdf\Autoloader::register();

// reference the Dompdf namespace
use Dompdf\Dompdf;

$tabela = "&lt;table&gt;";

for($i = 0; $i &lt;= 10; $i++) {
    $resultado = $i * 5;
    $tabela .= "&lt;tr&gt;&lt;td&gt;$i * 5 = &lt;/td&gt;&lt;td&gt;$resultado&lt;/td&gt;&lt;/tr&gt;";
}

$tabela .= "&lt;/table&gt;";
// instantiate and use the dompdf class
$dompdf = new Dompdf();
$dompdf-&gt;loadHtml($tabela);

// (Optional) Setup the paper size and orientation
$dompdf-&gt;setPaper('A4', 'landscape');

// Render the HTML as PDF
$dompdf-&gt;render();

// Output the generated PDF to Browser
$dompdf-&gt;stream();

?&gt;
</pre>
</div>
</div>

<div id="outline-container-org1cf26fc" class="outline-3">
<h3 id="org1cf26fc"><span class="section-number-3">1.4</span> Exercício 2</h3>
<div class="outline-text-3" id="text-1-4">
<p>
Utilizando o exemplo anterior, receba do usuário um valor e imprima no arquivo PDF a tabuada da multiplicação do valor selecionado.
</p>
</div>
</div>

<div id="outline-container-org426358a" class="outline-3">
<h3 id="org426358a"><span class="section-number-3">1.5</span> Nome do arquivo PDF</h3>
<div class="outline-text-3" id="text-1-5">
<p>
Você pode alterar o nome do arquivo ajustando um argumento para <code>$dompdf-&gt;stream()</code>:
</p>

<p>
Para salvar o arquivo como <code>saida.pdf</code> use:
</p>

<pre class="example">
$dompdf-&gt;stream("saida.pdf");
</pre>
</div>
</div>

<div id="outline-container-orgecb9b1e" class="outline-3">
<h3 id="orgecb9b1e"><span class="section-number-3">1.6</span> Exercício 3</h3>
<div class="outline-text-3" id="text-1-6">
<p>
Crie uma página que recebe o nome do usuário e um valor, imprima um título com o nome selecionado <code>&lt;h1&gt;Fulano&lt;/h1&gt;</code> e a tabuada do número escolhido em forma de tabela em um pdf com o nome digitado (exemplo: fulano.pdf).
</p>
</div>
</div>

<div id="outline-container-org5be1725" class="outline-3">
<h3 id="org5be1725"><span class="section-number-3">1.7</span> Exercício 4</h3>
<div class="outline-text-3" id="text-1-7">
<p>
Utilizando a tabela Usuarios criada na <a href="https://github.com/maurojh/PHP-Aula08-ex05">aula 8</a> gere um arquivo PDF usando dompdf que mostre todos os nomes e emails de todos os usuários cadastrados, cadastre ao menos 5 usuários antes.
</p>
</div>
</div>
</div>
</div>
<div id="postamble" class="status">
<p class="date">Created: 2019-11-05 ter 19:00</p>
<p class="validation"><a href="http://validator.w3.org/check?uri=referer">Validate</a></p>
</div>
</body>
</html>

