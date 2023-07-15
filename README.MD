## DNC Coffee - versão 1

### Uso do Bootstrap

O Bootstrap é um framework de código aberto amplamente utilizado para o desenvolvimento de interfaces responsivas para a web. Ele oferece um conjunto de estilos CSS, componentes e scripts JavaScript prontos para uso, o que facilita a criação de páginas web modernas e esteticamente agradáveis.

### Instalação

Para utilizar o Bootstrap em um projeto, é necessário incluir os arquivos CSS e JavaScript do framework em sua página HTML. Neste projeto, foram utilizadas as versões 5.3.0-alpha3 do Bootstrap.

Os links para os arquivos CSS e JavaScript do Bootstrap são adicionados no cabeçalho do documento HTML da seguinte maneira:

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KK94CHFLLe+nY2dmCWGMq91rCGa5gtU4mk92HdvYe+M/SXH301p5ILy+dN9+nJOZ" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ENjdO4Dr2bkBIFxQpeoTz1HIcje39Wm4jDKdf19U8gI4ddQ3GYNS7NTKfAdVQSZe" crossorigin="anonymous"></script>
```

### Tecnologias Utilizadas

- **HTML**: Foi utilizada a estrutura básica da página e seus elementos.
- **Bootstrap**: O framework foi usado para criar o layout, estilizar elementos e adicionar comportamentos interativos.

### Explicação dos Cards

Nesta aplicação, foram utilizados quatro cards para exibir informações sobre a DNC Coffee. Cada card é representado por um elemento `<article>` com a classe `card`. A classe `m-3` adiciona margem ao redor de cada card, enquanto a classe `border-1` adiciona uma borda sutil. A classe `rounded-2` define os cantos arredondados.

Cada card contém uma imagem, que é exibida no topo do card. A imagem é definida pelo elemento `<img>` com a classe `card-img-top`. As imagens estão localizadas no diretório `./assets/imgs/` e possuem o texto alternativo (atributo `alt`) para acessibilidade.

A seção de conteúdo de cada card está dentro de um elemento `<div>` com a classe `card-body`. O texto é definido pelo elemento `<p>` com a classe `card-text` e cor branca (`text-white`). O fundo do `<div>` é definido pela classe `bg-black` para dar contraste ao texto.

### Modal

O Bootstrap fornece um componente chamado modal para criar janelas modais. No projeto DNC Coffee, o modal é usado para exibir informações sobre a empresa quando o usuário clica no link "Sobre" no navbar.

O modal é definido dentro de um elemento `<div>` com a classe `modal` e um ID único (`sobre`). O botão de fechar o modal possui a classe `btn-close` e o atributo `data-bs-dismiss="modal"` para fechar o modal quando clicado.

O conteúdo do modal é definido dentro do elemento `<div>` com a classe `modal-content`. O texto e a imagem são adicionados dentro deste elemento.

### Conclusão

Neste projeto, o Bootstrap foi utilizado para criar um layout responsivo e estilizar elementos como o navbar, cards e modal. O framework facilitou o desenvolvimento, fornecendo estilos pré-definidos e componentes interativos que melhoram a experiência do usuário. Com o Bootstrap, é possível criar páginas web modernas e atraentes de forma mais eficiente.

Qualquer dúvida ou sugestão, pode me contatar! :heart:
