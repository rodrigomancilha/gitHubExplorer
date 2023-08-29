## Configurando a Aplicação 
-[] yarn init -y
-[] yarn add react
-[] yarn add react-dom

## Configurando o Babel
-[] yarn add @babel/core @babel/cli/ @babel/preset-env -D
-[] yarn babel src/index.jsx --out-file dist/bundle.js
-[] yarn add @babel/preset-react -D

## Configurando o Webpack
-[] yarn add webpack webpack-cli -D
-[] yarn add babel-loader -D
-[X] yarn webpack 
-[] yarn add html-webpack-plugin -D
-[] yarn add webpack-dev-server -D
-[X] yarn webpack serve

## Configurando o Ambiente Dev e Produção
-[] NODE_ENV=production yarn webpack
-[] yarn add cross-env -D

## Configurando Arquivos CSS
-[] yarn add style-loader css-loader -D

## Configurando o SASS
-[] yarn add node-sass -D
-[] yarn add sass-loader -D

## Configurando o Fast Refresh no Webpack
-[] yarn add -D @pmmmwh/react-refresh-webpack-plugin react-refresh

## Configurando o TypeScript
-[] yarn add typescript -D
-[] yarn tsc --init
-[] yarn add @babel/preset-typescript -D
-[] yarn add @types/react-dom -D
-[] yarn add @types/react -D