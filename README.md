# CourseManager

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.3.5.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Introdução ao Angular

## Criando primeira aplicação

ng new course-manager

## Carregar a aplicação

ng serve

## Porta padrão do Angular

http://localhost:4200/


## Entendendo a estrutura de pastas do Angular

- package.json : é nesse arquivo que irá conter todas as dependencias da aplicação; Nele podemos editar as configurações de inicialização;
- angular.json : possui as informaçãoes globais da aplicação, arquivo que vai configurar várias propriedades globais, vai definir qual o arquivo
que vamos inicializar a nossa aplicação.
	- dentro do angular.json, podemos falar de alguns itens: assets: representa a parte estatica da aplicação como fotos, videos, arquivos, 
	na pasta de src/styles defino os estilos globais que serão propagados em todos os componentes, "index.html" é a pagina da nossa aplicação
	o angular utiliza o padrão single page aplicattion, nesse padrão toda a pagina está envelopada em uma unica pagina, um unico componente. "main" 
	é responsavel por fazer o bootstrap da nossa aplicação, ou seja para inicializar a aplicação.

- node_modules : contem todas as pastas de dependencia da nossa aplicação
- a pasta raiz é a src(source), o mains é respnsável pela inicialização da aplicação, é ele que faz o bootstrap


Angular : é modular e mesmo quando não criamos ele já possui um modulo raiz que já engloba todos os seus componentes. um modulo é como se fosse um limitador de contexto.

Podemos criar os componentes como: login, cadastro e outros...

## Importar modulos

eu importo no arquivo: app.module.ts ,  e isso ajuda a importar apenas o que vamos utilizar e reduzir o tamanho do arquivo

Ele apenas exibe o atributo: One no way data byte
ele lê e altera o valo e exibe: Two way data bye

## Nomenclatura em Angular



