# HTML5

### Estrutura básica

Um elemento HTML é formado pela `tag` de abertura e os seus atributos, o conteúdo e uma `tag` de fechamento. Porém, existem `tags` que não precisam de fechamento. 

Com esses elementos podemos adicionar conteúdos, alterar tamanho e forma das fontes e adicionar diferentes mídias à nossa página na web. 

#### Estrutura básica de um arquivo HTML

`<!DOCTYPE html>`

`<html>`

``<head>`

`<meta>`

`<title> </title>`

`</head>`

`<body>`

`</body>`

`</html>`

  A primeira linha do nosso documento deve ser o `<!DOCTYPE html>` , ela apenas diz ao navegador que ele está lidando com um arquivo HTML5. Os elementos HTML vem logo em seguida. 

#### `<html>`

é uma raiz do seu documento, onde todos os elementos HTML devem estar concentrados. Nela informamos ao navegador qual idioma será usado nesse documento, através da `lang` para o português brasileiro usamos pt-BR.

#### `<head>`

Contém elementos que serão lidos pelo navegador, como os metadados. Um exemplo deles é o `charset` que é a codificação de caracteres, sendo a mais comum a `UTF-8` . Assim como no JavaScript com a tag `script` , o CSS através das tags `style` e `link` .

#### `<body>`

Dentro da `<body>` colocamos todo o conteúdo visível ao usuário como: textos, imagens, vídeos e etc.

### Semântica

A semântica permite descrever o nosso conteúdo mais precisamente.

#### `<section>`

Representa uma seção genérica de conteúdo quando não houver um elemento mais específico para isso. Como uma lista de artigos. 

#### `<header>`

É o cabeçalho da sua página ou de uma seção da página que normalmente contém logotipos, menus, campos de busca.

#### `<article>`

Representa um conteúdo relevante dentro da sua página, como um post de blog, uma notícia em uma barra lateral ou em um bloco de comentários. O `<article>` pode conter outros elementos como uma header, cabeçalho, parágrafos e imagens. 

#### `<aside>`

Engloba conteúdos relacionados ao conteúdo principal da página, como artigos, biografia do autor e publicidade. Geramente são representadas como barras laterais. 

#### `<footer>`

Ele representa o rodapé da página, pois é aceito dentro de vários elementos como o `article` e `section` e até o `body` . Conteúdos como autor e links relacionados são aceitos no `<footer>` .

#### `<h1>-<h6>`

Não foram criados na versão 5 do HTML e nem são específicos para semântica, mas serve para esse propósito. Trazem a importância de um título dentro de uma página, sendo `<h1>` o mais importante e `<h6>` o menos. Use apenas uma `<h1>` por página, pois ele representa o objetivo da sua página. 

### Textos e links

O `<p>` representa um parágrafo, mas ele não suporta apenas texto, podemos adicionar imagens, código, vídeos e vários outros tipos de conteúdo dentro dele.

`<h1>` Título da página `</h1>`

`<h2>` Título da seção `</h2>`

`<h3>` Título de artigo `</h3> `

`<p>` Conteúdo do artigo `</p>`

Outro elemento extremamente utilizado é o `<a>`  que significa uma âncora, que representa um hyperlink, sendo ele que interliga vários conteúdos e páginas na web.

`<a>` Link `</a>`

O `href` representa o hyperlink para a sua âncora aponta, podendo ser uma página do seu ou de outro site, e-mail (mailto), telefone (tel).

`< a href = "linkedin.com/in/...."> LinkedIn </a>`

``< herf = "mailto: rebsbra@gmail.com" > E-mail </a>`

O `target` serve para nos ajudar a abrir nossos links em outra aba do navegador usando o valor `_blank`

`< a target = "_blank" > Link </a>`

### Imagens

 Para acrescentar uma imagem usamos a `tag` `<img>`. Essa `tag` não utiliza fechamento. 

O elemento `img` é bem simples, contém apenas 2 atributos próprios, o `src` e o `alt`. 

O `src` é um elemento obrigatório e guarda o caminho para a imagem que você quer mostrar na página. Pode ser uma imagem dentro do site ou de outro lugar. 

O `alt` não é obrigatório, porém é altamente recomendado por melhorar a acessibilidade, ele mostra a descrição da imagem caso ela não carregue e leitores de tela usam esse atributo para descrever a imagem para o usuário saber o que ela significa. 

`<img>`

`<img src ="img/gato.jpg"> `

`<img alt = "Foto do gato">`

- Se a imagem que você quer adicionar estiver dentro da pasta do seu projeto html, digita apenas o nome do arquivo. 
- Caso essa imagem estivesse em outra pasta, digite `img/nome do arquivo`
- Se a imagem estivesse em um site, digite `http://www.....`

### Listas

Listas servem para agrupar uma coleção de itens, como uma lista de ingredientes ou uma lista com contatos.

O elemento `ul` cria uma lista não ordenada, onde a ordem dos elementos não é importante, e é representada com pontos, círculos ou quadrados. 

O `<ol>` serve para criar listas ordenadas, nesse caso a ordem importa, portanto elas são representadas com números, algarismos romanos ou letras. 

O elemento `li` é um item dentro de uma dessas listas. Um `<li>` pode conter vários tipos de conteúdo, como parágrafos, imagens e até outras listas. 

`<ul>`

- Item 1
- Item 2

`<ol>`

1. Item 1
2. Item 2

`<li>`









  

