#exercicio-s1

# Então, o que é HTML e CSS?

#### 1. HTML

O acrônimo HTML, do inglês _Hypertext Markup Language_ (Linguagem de Marcação de Hipertexto), serve para dar significado e organização ao conteúdo da interface de um site, ou seja, é uma ferramenta usada para definir a estrutura do documento. Consiste de uma série de elementos que delimitam e agrupam diferentes partes do conteúdo, para que o mesmo apareça ou atue de uma determinada maneira na interface de comunicação com o usuário.

Ao contrário do que costuma pensar, o HTML não é uma linguagem de programação, portanto, não é possível desenvolver páginas com recursos dinâmicos.

Mas você deve estar se perguntando: o que é um hipertexto? Um hipertexto faz referência a um texto com blocos interconectados contendo palavras, imagens, cabeçalhos, tabelas e outros elementos, que podem ou não apontar para outros hipertextos, caminhos esses conhecidos como hiperligações, _hiperlinks_ ou apenas _links_ .

Mas como ocorre a transformação do conteúdo de um documento em estruturas HTML na interface de um site? Ele marca a informação com _tags_(etiquetas), que definem se o elemento será um parágrafo, um cabeçalho, um link , um trecho de uma citação, um rodapé, uma seção de um conteúdo, e assim por diante.

As principais partes de um elemento são:

- _Tag_ de Abertura <p> (marca o início de um elemento);
- _Tag_ de Fechamento </p> (marca o fim de um elemento);
- Conteúdo (parte conceitual/semântica delimitada entre o início e o fim da _tag_); e
- Atributos (são comandos específicos que damos a uma _tag_ para que ela se comporte de uma determinada maneira).

A estrutura básica de todo documento HTML é:

- **<!DOCTYPE html>** - Declara ao navegador que a linguagem usada é  HTML;
- **<html><html>** - O elemento <html> envolve todo o conteúdo da página HTML;
- **<head><head>** - O elemento <head> é o local onde se incluem todos os elementos não renderizáveis da página;
- **<meta charset='utf-8'>** - Elementos de metadados que definem o conjunto de caracteres que o documento deve usar.
- **<tittle></tittle>** - Define o título da página; e
- **<body></body> - Define todos os elementos renderizáveis da página, ou seja, todo o corpo da página HTML.

#### 2. CSS

CSS é a sigla para o termo em inglês _Cascading Style Sheets_ que, traduzido para o português, significa Folha de Estilo em Cascatas. É usado para estilizar elementos escritos em uma linguagem de marcação como o HTML. Com ela é possível alterar a cor do texto, fundo da página, fonte e espaçamento entre parágrafos. Também podeé possível criar tabelas, usar variações de _layouts_, ajustar imagens e assim por diante.

Mas como funciona o CSS?

O CSS usa uma sintaxe simples baseada em inglês com um conjunto de regras que o governam. Tem um seletor e um bloco de declaração. 

O seletor aponta para o elemento HTML que você se deseja estilizar, enquanto o bloco de declaração contém uma ou mais declarações separadas por ponto e vírgula. Cada declaração inclui um nome de propriedade CSS e um valor, separados por dois pontos. Uma declaração CSS sempre termina com um ponto-e-vírgula e os blocos de declaração são cercados por chaves.

Vamos simular um exemplo. Digamos que o objetivo é mudar a fonte de uma tag h1. Para isso podemos usar h1 {font-size: 20px;}

- h1 – é o seletor. Neste caso selecionamos o h1.
- font-size – é a declaração que contém  a propriedade (font-size) e o valor é (20px).

O CSS foi criado para ser trabalhado em conjunto com o HTML. Devido ao conceito que utiliza (a separação entre apresentação e conteúdo), a tecnologia CSS tem um padrão muito amplo, com especificações, benefícios e possibilidades muito grandes.

Atualmente, você encontrará o CSS na maioria dos sites, já que é um requisito tão importante como a própria linguagem de marcação. Portanto, não deixe de implantá-lo!