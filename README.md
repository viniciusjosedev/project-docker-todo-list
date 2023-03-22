<h1 align='center' id='Título-e-Imagem-de-capa'>Docker Todo List</h1>

<p align='center'>
<img src='./public/favicon.svg' width="230" heigth="259"/>
</p>


## Bradges

<p align='left'>
<img src='https://img.shields.io/badge/STATUS-FINALIZADO-Green' width='250px'></img>
</p>

<h2>Deploy: https://app-receitas.surge.sh</h2>

</br>


## Execução

### Para instalar o projeto na sua máquina, faça antes o clone do repositório

### Para clones com HTTPS:

```bash
  git clone https://github.com/viniciusjosedev/project-recipes-app.git
```

### Para clones com SSH:

```bash
  git clone git@github.com:viniciusjosedev/project-recipes-app.git
```

### Para clones com GitHub CLI:

```bash
  gh repo clone viniciusjosedev/project-recipes-app
```

### Depois de clonado, abra a o terminal na raiz do projeto e rode o seguinte comando:

```bash
  npm i && npm start
```

### Pronto! Com isso a aplicação irá rodar na sua máquina localmente.

## Descrição do projeto

### Projeto realizado mediante a necessidade da prática em conceitos inicialmente abordados de forma teórica. Diversos conceitos foram abordados neste projeto, mas precisamente, tivemos uma livre escolha de quais tecnologias/ferramentas usar.
### Neste projeto em específico, praticamos ainda mais a forma de se desenvolver uma aplicação em React. Usando componentes de funções, e junto com eles, tambem usamos os conhecimentos de hooks. Hooks esses que foram tanto nativos quanto personalizados.
### Além disso, praticamos requisições para API's, junto com isso, veio a necessidade de tratar essas requisições como uma Promise e então encaminhar os resultados para a tela do usuário.
### API('s) usada(s):

### End-Point de receitas de comidas (existem variações): https://www.themealdb.com/api/json/v1/1/ - :heavy_check_mark:
### End-Point de receitas de bebidas (existem variações): https://www.themealdb.com/api/json/v1/1/ - :heavy_check_mark:

## :hammer: Funcionalidades :hammer:

### A aplicação se inicia unica tela na rota '/'.
### Nesta tela, o usuário poderá efetuar um login.
### Logo em seguida, o usuário é redirecionado para a rota '/meals'. Nesta tela, ele poderá usar as mais diversas ferramentas de filtros de receitas.

## :computer: Tecnologias/Linguagens utilizadas :computer:

### Tecnologias: - HTML5, CSS6, JS6, SASS e CSS Modules - :heavy_check_mark:
### Bibliotecas: - react, prop-types@15, bootstrap, reactstrap, react-icons, eslint e stylelint - :heavy_check_mark:

## Pessoas Desenvolvedoras do Projeto.
### Projeto realizado em conjunto com a empresa de tecnologia Trybe, que foi a responsável pela criação dos testes com o Cypress, fazendo-se assim, toda a estrutura necessária para um bom desenvolvimento orientado a testes (TDD).
### Além dos testes com o Cypress, toda a estrutura inicial do projeto foram feitas pela Trybe, isso inclui: todos os scripts no packge.json (com excessão do "erro"), estrutura inicial das pastas e arquivos.
### Todas os demais adições dos arquivos/diretórios do projeto são de autoria do grupo 25, isso inclui: src/pages, src/components, src/api, src/helpers, src/styles, src/tests. As alterações dos demais arquivos soltos na pasta src/ também são de nossa autoria, isso inclui: App.jsx, index.js e index.css.
##### OBS 1: O arquivo setupTests.js já vem como default com o React na instalação feita (npx create-react-app .).
##### OBS 2: Todos os testes com o Cypress foram devidamente apagados, esta ação envolve proteger a autoria de código, respeitando assim as normas e regras internas da empresa de tecnologia Trybe.

### O denominado grupo 25 é formado por 5 pessoas, são elas: Felipe Matos, Gabriel Amaral, Marcio Araujo, Marco Haiat e Vinicius José.
