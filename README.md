# [Angular 14: aplique os conceitos e desenvolva seu primeiro CRUD](https://cursos.alura.com.br/course/angular-explorando-framework)

## Links

[Codigo do curso 2 posterior a esse](https://github.com/brunosantanati/angular14-evoluindo-a-aplicacao/)  
[GitHub repo - aula 1](https://github.com/alura-cursos/2438-angular-memoteca/tree/aula-1)  
[GitHub repo - aula 2](https://github.com/alura-cursos/2438-angular-memoteca/tree/aula-2)  
[GitHub repo - aula 3](https://github.com/alura-cursos/2438-angular-memoteca/tree/aula-3)   
[GitHub repo - aula 4](https://github.com/alura-cursos/2438-angular-memoteca/tree/aula-4)  
[GitHub repo - aula 5](https://github.com/alura-cursos/2438-angular-memoteca/tree/aula-5)  
[GitHub repo - aula 6](https://github.com/alura-cursos/2438-angular-memoteca/tree/aula-6) (projeto final)   
[Angular CLI](https://angular.io/cli)  

## Comandos utilizados no curso

```
Comandos Node (o Node é pré-requisito para instalar o Angular CLI)

Checar versões do Node instaladas:
nvm ls

Instalar versão específica do Node:
nvm install 16.16.0

Escolher versão do Node:
nvm use 16.16.0

----------

Instalação do Angular CLI:
npm install -g @angular/cli

----------

Dentro da pasta backend:

Criar o arquivo package.json:
npm init -y

Instalar o json-server para simular uma API:
npm i json-server

Após modificar o 'start' dentro do package.json rodar:
npm start
Se necessário apagar a pasta node_modules e rodar antes:
npm install

Acessar:
http://localhost:3000/pensamentos

----------

Dentro da pasta raiz do projeto:

Instalar dependencias:
npm install

Subir o servidor:
ng serve

Acessar:
http://localhost:4200/listarPensamento

----------

Outros comandos:

Ver versão do Angular CLI:
ng version

Criar projeto novo:
ng new <nome-do-projeto>
Exemplo de uso:
$ ng new memoteca
? Would you like to add Angular routing? Yes
? Which stylesheet format would you like to use? CSS

Exemplos de criação de componentes:
ng generate component componentes/cabecalho
ng g c componentes/rodape
ng g c componentes/pensamentos/criar-pensamento
ng g c componentes/pensamentos/listar-pensamento
ng g c componentes/pensamentos/pensamento
ng g s componentes/pensamentos/pensamento
ng g c componentes/pensamentos/excluir-pensamento
ng g c componentes/pensamentos/editar-pensamento

Subir o servidor para acessar a aplicação Angular no browser:
ng serve
``` 
