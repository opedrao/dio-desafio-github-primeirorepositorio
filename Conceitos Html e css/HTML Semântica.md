

# HTML Semântica

O **HTML semântica** é a forma de deixar o site com suas informações bem explicadas e compreensíveis para o computador, ajudando até mesmo em sua busca no Google e facilitando o entendimento de leitores de acessibilidade. Com o **HTML semântico**, ficou muito mais fácil de interpretar páginas. 

### header

O *<header>* é utilizado para representar o cabeçalho de um documento ou seção declarado no HTML. Nele podemos inserir elementos de *<h1>* a *<h6>*, até elementos para representar imagens, parágrafos ou mesmo listas de navegação.

Exemplo de uso de *<header>*: 

```html
<header>
     <h1>Título da página</h1>
     <h2>Subtítulo da página</h2>
</header>
```

### section

O elemento *<section>* representa uma seção dentro de um documento e geralmente contém um título, o qual é definido por meio de um dos elementos entre *<h1>* e *<h6>*. Podemos utilizar o *<section>*, por exemplo, para descrever as seções/tópicos de um documento.

Exemplo de uso de *<section>*: 

```html
<section>
    <h3>Seção 1</h3>

    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod ...</p>
</section>
```

### article

Utilizamos o elemento *<article>* quando precisamos declarar um conteúdo que não precisa de outro para fazer sentido em um documento HTML, por exemplo, um artigo em um blog. É recomendado identificar cada *<article>* com um título.

Exemplo de uso de *<article>*: 

```html
<article>
    <h3>Título do artigo 1</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod ...</p>
</article>
<article>
    <h3>Título do artigo 2</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod ...</p>
</article>

```

### nav

O elemento *<nav>* é utilizado quando precisamos representar um agrupamento de links de navegação, que, por sua vez, são criados com os elementos *<ul>*, *<li>* e *<a>*.

Exemplo de uso de *<nav>*: 

```html
<nav>
 <ul>
 <li><a href=”#”>pagina 1</a></li>
 <li><a href=”#”>pagina 2</a></li>
 <li><a href=”#”>pagina 3</a></li>
 <li><a href=”#”>pagina 4</a></li>
 </ul>
</nav>
```

### aside

O elemento *<aside>* é utilizado quando precisamos criar um conteúdo de apoio/adicional ao conteúdo principal. Por exemplo, ao falar de HTML semântico, podemos indicar ao leitor outros conteúdos sobre a linguagem HTML como sugestão de leitura complementar.

Exemplo de uso de *<aside>*: 

```html
<aside>
  <nav>
    <ul>
        <li>Link 1</li>
        <li>Link 2</li>
        <li>Link 3</li>
        <li>Link 4</li>
     </ul>
  </nav>
</aside>
```

### main

O elemento *<main>* especifica o conteúdo principal e, consequentemente, de maior relevância dentro da página. Para ser considerada bem construída, uma página deve apresentar apenas um conteúdo principal.

Exemplo de uso de *<main>*: 

```html
<main>
  <h2>Titulo</h2>

  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod ...</p>

  <article>
     <h3>Subtítulo</h3>
        <p>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum...</p>
   </article>
</main>
```

### figure

O elemento *<figure>* é uma marcação de uso específico para a inserção de uma figura. Para incluir a descrição dessa figura, podemos utilizar o elemento *<figcaption>*.

Exemplo de uso de *<figure>*: 

```html
<figure>
  <img src=”http://meusite.com.br/assets/imagem.jpg” alt=”Imagem”>
</figure>
```

### footer

O elemento *<footer>* representa um rodapé de um documento, como a área presente no final de uma página web. Normalmente é utilizado para descrever informações de autoria, como nome e contato do autor, e data de criação do conteúdo.

Exemplo de uso de *<footer>*: 

```html
footer
O elemento <footer> representa um rodapé de um documento, como a área presente no final de uma página web. Normalmente é utilizado para descrever informações de autoria, como nome e contato do autor, e data de criação do conteúdo.

Exemplo de uso de <footer>:
```

### Semântica no nível do texto

Além da semântica estrutural, o HTML nos permite descrever o significado de um conteúdo em nível de texto utilizando um conjunto de elementos semânticos. Assim, é possível, por exemplo, destacar os trechos de texto que devem receber algum tipo de destaque.

### a

A principal função do elemento *<a>* é descrever um link, conectando os diversos documentos de um site e permitindo a navegação por esse conteúdo. Normalmente esses documentos estão relacionados por compartilharem um assunto em comum.

Exemplo de uso de *<a>*: 

```html
<a href=”http://www.devmedia.com.br” alt=”DevMedia”>DevMedia</a>
```

### em

O elemento *<em>* é utilizado quando desejamos enfatizar um trecho ou palavra no texto, indicando que ela contribui de forma mais relevante para o sentido/compreensão do conteúdo.

Exemplo de uso de *<em>*: 

```html
<p>Você <em>tem certeza</em> que essa definição está correta?</p>
```

### strong

O elemento *<strong>* também é utilizado para destacar uma parte do texto. Sua principal diferença em relação ao elemento *<em>* é que *<em>* pode alterar o propósito de uma frase, como vimos anteriormente.

Exemplo de uso de *<strong>*:

```html
<p>Compreender esses elementos HTML é importante porque
<strong>possibilita o desenvolvimento de soluções web modernas</strong>.</p>
```

### cite e q

O elemento *<cite>* é utilizado para declarar que naquele trecho há uma citação, isto é, um trecho de texto que não foi escrito pelo autor do conteúdo. Normalmente utiliza-se o *<cite>* em conjunto com o elemento *<q>*, responsável por apresentar o conteúdo retirado de outra fonte.

Exemplo de uso de *<cite>* e *<q>*:

```html
<p>
<q>Lorem ipsum dolor sit amet, consectetur </q> - <cite>http://br.lipsum.com/</cite>.
</p>
```

### time

O elemento *<time>* é utilizado para representar datas. Assim, caso seja necessário informar a data em que um conteúdo foi escrito, podemos declarar a tag *<time>* e acrescentar a ela o atributo datetime para escrever a data de forma padronizada.

```html
<time datetime=”2017-04-07”>4/7</time>
```