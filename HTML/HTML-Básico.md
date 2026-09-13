# HTML Básico

HTML (HyperText Markup Language) é a linguagem usada para estruturar o conteúdo de páginas web.

## Estrutura básica

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Meu Site</title>
</head>
<body>

</body>
</html>


* <!DOCTYPE html> → informa que o documento usa HTML5
* <html> → elemento raiz da página
* <head> → informações da página
* <body> → conteúdo visível da página
* <title> → título exibido na aba do navegador

## Tags

HTML utiliza **tags** para definir a estrutura e o significado do conteúdo.

```html
<h1>Título</h1>
<p>Parágrafo</p>
```

A maioria das tags possui abertura e fechamento:

html
<tag>conteúdo</tag>


## Títulos

Existem 6 níveis de título:

html
<h1>Título principal</h1>
<h2>Subtítulo</h2>
<h3>Subtítulo</h3>


<h1> é o título de maior importância e <h6> o de menor.

## Parágrafos

html
<p>Este é um parágrafo.</p>


## Quebra de linha

html
<br>


Usada para quebrar uma linha.

## Links

html
<a href="https://www.google.com">Google</a>


* <a> → cria um link
* href → define o destino

Para abrir em uma nova aba:

html
<a href="https://www.google.com" target="_blank">Google</a>


## Imagens

html
<img src="imagem.jpg" alt="Descrição da imagem">


* src → caminho da imagem
* alt → descrição da imagem

## Listas

### Lista não ordenada

html
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>


### Lista ordenada

html
<ol>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ol>


* <ul> → lista com marcadores
* <ol> → lista numerada
* <li> → item da lista

## Atributos

Atributos adicionam informações ou configurações aos elementos.

html
<a href="https://google.com">Google</a>


Nesse exemplo, href é um atributo.

Outro exemplo:

html
<img src="foto.jpg" alt="Minha foto">


src e alt são atributos.

## id e class

São usados para identificar e agrupar elementos, sendo muito utilizados posteriormente com CSS e JavaScript.

html
<p id="principal">Olá</p>

<p class="texto">Primeiro</p>
<p class="texto">Segundo</p>


* id → identifica um elemento específico
* class → pode ser usada em vários elementos

## Comentários

Comentários não aparecem na página:

html
<!-- Este é um comentário -->


## HTML Semântico

HTML semântico utiliza tags que indicam o significado do conteúdo.

html
<header>Cabeçalho</header>
<nav>Menu</nav>
<main>Conteúdo principal</main>
<section>Seção</section>
<article>Artigo</article>
<footer>Rodapé</footer>


Isso melhora a **organização, acessibilidade e compreensão do código**.

## Resumo

text
HTML → estrutura e significado
CSS → aparência
JavaScript → comportamento e interatividade

