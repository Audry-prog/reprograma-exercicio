#exercicio-s1

# Então, o que é HTML e CSS?

__________

![Imagem vetor de HTML e CSS ](https://github.com/Audry-prog/reprograma-exercicio/blob/master/html_css.jpg)

##### _Escrito por Audry  Ibragimova._
##### _Postado em 15 de agosto de 2020._
____________
#### 1. HTML

O acrônimo HTML, do inglês _Hypertext Markup Language_ (Linguagem de Marcação de Hipertexto), serve para dar significado e organização ao conteúdo da interface de um site, ou seja, é uma ferramenta usada para definir a estrutura do documento. Consiste de uma série de elementos que delimitam e agrupam diferentes partes do conteúdo, para que o mesmo apareça ou atue de uma determinada maneira na interface de comunicação com o usuário.

Ao contrário do que costuma pensar, o HTML não é uma linguagem de programação, portanto, não é possível desenvolver páginas com recursos dinâmicos.

Mas você deve estar se perguntando: o que é um hipertexto? Um hipertexto faz referência a um texto com blocos interconectados contendo palavras, imagens, cabeçalhos, tabelas e outros elementos, que podem ou não apontar para outros hipertextos, caminhos esses conhecidos como hiperligações, _hiperlinks_ ou apenas _links_ .

Mas como ocorre a transformação do conteúdo de um documento em estruturas HTML na interface de um site? Ele marca a informação com tags (etiquetas), que definem se o elemento será um parágrafo, um cabeçalho, um link , um trecho de uma citação, um rodapé, uma seção de um conteúdo, e assim por diante.

As principais partes de um elemento são:

![imagem da estrutura de um elemento html](https://github.com/Audry-prog/reprograma-exercicio/blob/master/estrutura-de-um-elemento-html.jpg)

- Tag de Abertura ``<p>`` (marca o início de um elemento);
- Tag de Fechamento ``</p>`` (marca o fim de um elemento);
- Conteúdo (parte conceitual/semântica delimitada entre o início e o fim da tag); e
- Atributos (são comandos específicos que damos a uma tag para que ela se comporte de uma determinada maneira).

A estrutura básica de todo documento HTML é:

- ``**<!DOCTYPE html>**`` - Declara ao navegador que a linguagem usada é  HTML;
- ``**<html><html>**`` - O elemento ``<html>`` envolve todo o conteúdo da página HTML;
- ``**<head><head>**`` - O elemento ``<head>`` é o local onde se incluem todos os elementos não renderizáveis da página;
- ``**<meta charset='utf-8'>**`` - Elementos de metadados que definem o conjunto de caracteres que o documento deve usar.
- ``**<tittle></tittle>**`` - Define o título da página; e
- ``**<body></body>**`` - Define todos os elementos renderizáveis da página, ou seja, todo o corpo da página HTML.

#### 2. CSS
<br>
CSS é a sigla para o termo em inglês Cascading Style Sheets que, traduzido para o português, significa Folha de Estilo em Cascatas. É usado para estilizar elementos escritos em uma linguagem de marcação como o HTML. Com ela é possível alterar a cor do texto, fundo da página, fonte e espaçamento entre parágrafos. Também podeé possível criar tabelas, usar variações de layouts, ajustar imagens e assim por diante.

Mas como funciona o CSS?

O CSS usa uma sintaxe simples baseada em inglês com um conjunto de regras que o governam. Tem um seletor e um bloco de declaração.
<br>
O seletor aponta para o elemento HTML que você se deseja estilizar, enquanto o bloco de declaração contém uma ou mais declarações separadas por ponto e vírgula. Cada declaração inclui um nome de propriedade CSS e um valor, separados por dois pontos. Uma declaração CSS sempre termina com um ponto-e-vírgula e os blocos de declaração são cercados por chaves.

Vamos simular um exemplo. Digamos que o objetivo é mudar a fonte de uma tag h1. Para isso podemos usar h1 {font-size: 20px;}

- **h1** – é o seletor. Neste caso selecionamos o h1.
- **font-size** – é a declaração que contém  a propriedade (font-size) e o valor é (20px).

O CSS foi criado para ser trabalhado em conjunto com o HTML. Devido ao conceito que utiliza (a separação entre apresentação e conteúdo), a tecnologia CSS tem um padrão muito amplo, com especificações, benefícios e possibilidades muito grandes.

Atualmente, você encontrará o CSS na maioria dos sites, já que é um requisito tão importante como a própria linguagem de marcação. Portanto, não deixe de implantá-lo!
<br>

#### _Referências:_

##### _1. HOSTINGER TUTORIAIS. O que é HTML? Guia Básico para Iniciantes. <https://www.hostinger.com.br/tutoriais/o-que-e-html-conceitos-basicos/> Acesso em: 15 de ago de 2020._

##### _2. HOSTINGER TUTORIAIS. O que é CSS? Guia Básico para Iniciantes. <https://www.hostinger.com.br/tutoriais/o-que-e-css-guia-basico-de-css/> Acesso em: 15 de ago de 2020._

##### _3. MDN WEB DOCS MOZILLA. Css Básico. <https://developer.mozilla.org/pt-BR/docs/Aprender/Getting_started_with_the_web/CSS_basico> Acesso em: 15 de ago 2020._

##### _4. TREINAWEB. O que é e como começar com HTML e CSS?  <https://www.treinaweb.com.br/blog/o-que-e-e-como-comecar-com-html-e-css/> Acesso em: 15 de ago de 2020._
