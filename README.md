### Whatsapp Web 

![Whatsapp Web](/images/whatsapp-web-material-ui.jpg)

- Atualização: 14 de agosto de 2019 
- Criação: 06 de junho de 201
- Prática : @douglasabnovato

### Ferramentas : 

![ReactJS](/images/logo-reactjs.jpg)
![Git](/images/logo-git.png)
![Github](/images/logo-github.png)
![HTML/CSS/Javascript](/images/logo-html-css-js.jpeg)
![VSCode](/images/logo-VSCode.png)
![Yarn](/images/logo-yarn.png)
![Nodejs](/images/nodejs.png)
![Material Design Lite Google](/images/logo-material-design-lite-google.jpg)

### Layout do Whatsapp Web em ReactJS com Material UI 

- Whatsapp Web utilizando material-ui, uma biblioteca visual para ReactJS.
- Integração do Material UI com ReactJS
- instalar o Material UI: `npm install @material-ui/core`
- adicionar os componentes ícones: `npm install @material-ui/icons`
- adicionaremos os links das fonts Roboto e Fonts Icon
- `<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto:300,400,500">`
- `<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">`
- fundo acinzentado no body, no index.css
````js
body {
    margin: 0;
    padding: 0;
    font-family: sans-serif;
    background: "#dfdfdf";
}
````
- função withStyles
- injetamos um CSS customizado
- Fonts Icon:`@material-ui/icons` - ícones que queremos
- componentes estilizados e padronizados do Material UI
- `@material-ui/core` - ícones que queremos

:. De [Blog Rocketseat - Integração do Material UI com ReactJS - Higo Ribeiro](https://blog.rocketseat.com.br/react-material-ui/)