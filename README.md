# Trabalho-final-de-html.css-lays-e-Natalia
Sobre as histórias de Escravos no Brasil
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="histo.css">
    <title>Document</title>
</head>
<body>
  <main>
  <nav ></nav><h1>" A chegada dos escravos em terras brasileiras."</h1></nav>
  <section><p> A escravidão no Brasil tem consequencias até hoje na sociedade brasileiras,vemos que apesar de estudos e conhecimentos 
    e leis grande parte da população ainda usam falas racitas gestos ou siplismente desprezam pessoas negras só pela cor da pele.
    Para mudar isso precisamos conhecer mais aprofundado o que foi o período de escravidão nas terras brasileiras.
  </p></section>
  <aside><p>A escravidão no Brasil foi um dos capítulos mais tristes e cruéis da nossa história. Durante mais de 300 anos,
     milhões de africanos foram trazidos à força para trabalhar nas plantações de açúcar, nas minas e em outras atividades econômicas que sustentaram a colonização. 
     Esses homens e mulheres eram tratados como propriedade, sem direitos, sendo forçados a viver em condições desumanas. Mesmo após a abolição da escravidão
      em 1888, as marcas desse sistema ainda persistem, com profundas desigualdades sociais e raciais que afetam a nossa sociedade até hoje.
      
   Refletir sobre esse período é essencial para entendermos as injustiças do passado e como elas ainda influenciam a nossa realidade.</p></aside>
  <article><img src="escravos .jpg"></article>
  <figure><h2> As leis que foram criadas para abolir a escravidão</h2></figure>
  <footer><ol>
    <li>Lei de Eusébio de Queiroz(1850)</li>
    <li>Lei do ventrehivre(1871)</li>
    <li>Lei Aurea(1888)</li>

  </ol>
  <a href="pagina2.html"></a>
    <a href="folha3.html"></a>
    <a href="Folha 4.html"></a>
    <a href="folha 5.html"></a>
</footer>
  <header>
    <a href="mundoeducacao.uol.com.br/historiadobrasil/as-leis-abolicionistas.htm">clique aqui para saber mais.</a>
  </header>
  </main>
</body>
</html>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    font-family: arial, sans-serif;
    line-height: 1.6;
    background-color: rgb(235, 165, 75);
}
main{
    display: grid;
    grid-template-areas: 
    " header header"
    "nav section"
    "aside article"
    "footer footer";
    grid-template-columns: 1fr 3fr;
    gap: 20px;
    padding: 20px;
}
h1{
    grid-area: header;
    text-align: center;
    color: darkred;
}
a href{
    background-color: burlywood;
    padding: 15px;
    border-radius: 5px;
}
nav{
    grid-area: nav;
}
section{
    grid-area: section;
    background-color: cadetblue;
    padding: 15px;
    border-radius: 5px;
}
article{
    grid-area: article;
}
figure{
    margin-top: 10px;
}
footer{
    grid-area: footer;
}
ol{
    padding-left: 20px;
}
img{
    max-width: 100%;
    height: auto;
}
header a{
    text-decoration: none;
}
header a:hover{
    color: chartreuse;
}
@media(max-width:768px)
main{
    grid-template-areas:
    "header" 
    "nav"
    "section" 
    "aside" 
    "article"
    "footer";
    grid-template-columns:1fr;
    gap:10px;
}

h1{
    font-size: 1.5em;
    margin-bottom: 10px;
}
section, aside, footer{
    padding: 10px;
    font-size: 0.9em;
    background-color: blanchedalmond;
    box-shadow: none;
}
