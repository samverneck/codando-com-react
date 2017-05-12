# React.js Ninja: Módulo React + Webpack

## Curso de React.js Ninja: Módulo React + Webpack <b>[UDEMY]</b>(https://www.udemy.com/reactjs-ninja-modulo-react-webpack/learn/)

* Apresentando as configurações de ambiente
	
* Configuração básica do Webpack
    - Criar um package.json
        - npm init ou echo {} >> package.json
        > cat package.json
    - Instalar o webpack como dependência de desenvolvimento.
        - npm instal --save--dev webpack
        > cat package.json
    - Depois [...]
    - Criar um arquivo webpack.config.js
    - Configurar para ler um arquivo gerar o bundle.
    ```
    'use strict'
    const path = require('path')

    module.exports = {
        entry: path.join(__dirname, 'src', 'index'), 
        output: {
            path:path.join(__dirname, 'dist'),
            filename: 'bundle.js'
        }
    }
    ```
    - Criar o arquivo <b>src/index.js</b>.
    - Instalar o webpack globalmente 
    > npm i -g webpack
    - Gerar o bundle com webpack
    - Criar o arquivo index.html e adicionar o bundle.
* Usando o server do Webpack

* Modularizando uma aplicação

* Criando uma aplicação em React

* Modularizando a aplicação

* Configurando JSX no babel e sourcemaps no Webpack

* Configurando a aplicação para usar o React hot loader

* Colocando o hot loader para funcionar

* Configurando a ferramenta de lint

