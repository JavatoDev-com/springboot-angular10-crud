# Angular 10 CRUD with Spring Boot REST API

<p align="left">
In this article, I’m going to explain how we can integrate both Angular frontend with REST API developed using Spring Boot. Additionally, I’m covering full CRUD with angular 10.

Technologies Going to Use,

- Angular 10.1.5
- Bootstrap 4.0
- lodash 4.17
- Angular HttpClient

Main topics I’m going to discuss here,

- Up and Running Backend REST API
- Initializing Angular Project
    - Adding Additional Modules
        - How to install bootstrap with an angular application ?
        - Forms Modules in to the Angular Project
- Defining REST API Client with HttpClient
- Developing UI Components
    - Defining Routing and Main Menu
    - Author Registration UI Component
        - Registering Author
        - Loading Registered Users
    - Book Registration UI Component
        - Delete a Registered Book
        - Editing a Registered Book
        - Register Member UI Component
        - Library Main Window UI Component
- Conclusion


</p>

📄 Original Tutorial [Angular 10 CRUD with Spring Boot REST API](https://javatodev.com/angular-10-crud-with-spring-boot-rest-api/)

Related Articles 

 - [How to Create a Spring Boot Project](https://javatodev.com/how-to-create-a-spring-boot-project/)
 - [Spring Boot REST API CRUD With DynamoDB Tutorial](https://javatodev.com/spring-boot-dynamo-db-crud-tutorial/)
 - [Spring Boot REST API Using JPA, Hibernate, MySQL Tutorial](https://javatodev.com/spring-boot-mysql/)
 - [Database Migration Using Flyway in Spring Boot](https://javatodev.com/flyway-spring-boot/)

# SpringbootAngular10Crud

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.1.6.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).


<h1 align="center">Hi 👋, I'm Chinthaka Dinadasa</h1>
<h3 align="center">A Passionate Java Fullstack Developer from Sri Lanka and Author of JavatoDev.com</h3>

<!-- <p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=javatodev" alt="javatodev" /></a> </p> -->

<p align="left"> <a href="https://twitter.com/spbootdeveloper" target="blank"><img src="https://img.shields.io/twitter/follow/spbootdeveloper?logo=twitter&style=for-the-badge" alt="spbootdeveloper" /></a> </p>

<!-- - 👨‍💻 All of my projects are available at [https://chinthaka-dinadasa.github.io/portofolio/](https://chinthaka-dinadasa.github.io/portofolio/) -->

- 📝 I regularly write articles on [http://javatodev.com/](http://javatodev.com/)

- 💬 Ask me about **Spring Boot, Java, Vue JS, Angular**

- 📫 How to reach me **author@javatodev.com**

- 📄 Know about my experiences [https://www.linkedin.com/in/chinthakadinadasa/](https://www.linkedin.com/in/chinthakadinadasa/)

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/spbootdeveloper" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/twitter.svg" alt="spbootdeveloper" height="30" width="40" /></a>
<a href="https://linkedin.com/in/chinthakadinadasa" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="chinthakadinadasa" height="30" width="40" /></a>
<a href="https://stackoverflow.com/users/https://stackoverflow.com/users/1455919/chinthaka-dinadasa" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/stackoverflow.svg" alt="https://stackoverflow.com/users/1455919/chinthaka-dinadasa" height="30" width="40" /></a>
<a href="https://fb.com/chinthaka.dinadasa" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/facebook.svg" alt="chinthaka.dinadasa" height="30" width="40" /></a>
<a href="https://medium.com/@chinthaka-dinadasa" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/medium.svg" alt="@chinthaka-dinadasa" height="30" width="40" /></a>
<a href="/https://javatodev.com/feed/" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/rss.svg" alt="https://javatodev.com/feed/" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://angular.io" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/angularjs/angularjs-original.svg" alt="angularjs" width="40" height="40"/> </a> <a href="https://aws.amazon.com" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://getbootstrap.com" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/bootstrap/bootstrap-plain.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://cassandra.apache.org/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/apache_cassandra/apache_cassandra-icon.svg" alt="cassandra" width="40" height="40"/> </a> <a href="https://www.cypress.io" target="_blank"> <img src="https://raw.githubusercontent.com/simple-icons/simple-icons/6e46ec1fc23b60c8fd0d2f2ff46db82e16dbd75f/icons/cypress.svg" alt="cypress" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://www.elastic.co" target="_blank"> <img src="https://www.vectorlogo.zone/logos/elastic/elastic-icon.svg" alt="elasticsearch" width="40" height="40"/> </a> <a href="https://expressjs.com" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/> </a> <a href="https://flutter.dev" target="_blank"> <img src="https://www.vectorlogo.zone/logos/flutterio/flutterio-icon.svg" alt="flutter" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://gohugo.io/" target="_blank"> <img src="https://api.iconify.design/logos-hugo.svg" alt="hugo" width="40" height="40"/> </a> <a href="https://www.java.com" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/java/java-original-wordmark.svg" alt="java" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.jenkins.io" target="_blank"> <img src="https://www.vectorlogo.zone/logos/jenkins/jenkins-icon.svg" alt="jenkins" width="40" height="40"/> </a> <a href="https://www.elastic.co/kibana" target="_blank"> <img src="https://www.vectorlogo.zone/logos/elasticco_kibana/elasticco_kibana-icon.svg" alt="kibana" width="40" height="40"/> </a> <a href="https://laravel.com/" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/laravel/laravel-plain-wordmark.svg" alt="laravel" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://mariadb.org/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/mariadb/mariadb-icon.svg" alt="mariadb" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://www.microsoft.com/en-us/sql-server" target="_blank"> <img src="https://cdn.worldvectorlogo.com/logos/microsoft-sql-server.svg" alt="mssql" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.nginx.com" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/nginx/nginx-original.svg" alt="nginx" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://www.oracle.com/" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/oracle/oracle-original.svg" alt="oracle" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://sass-lang.com" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/sass/sass-original.svg" alt="sass" width="40" height="40"/> </a> <a href="https://spring.io/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="spring" width="40" height="40"/> </a> <a href="https://www.typescriptlang.org/" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/> </a> <a href="https://vuejs.org/" target="_blank"> <img src="https://devicons.github.io/devicon/devicon.git/icons/vuejs/vuejs-original-wordmark.svg" alt="vuejs" width="40" height="40"/> </a> <a href="https://vuetifyjs.com/en/" target="_blank"> <img src="https://bestofjs.org/logos/vuetify.svg" alt="vuetify" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=javatodev&show_icons=true&locale=en&layout=compact" alt="javatodev" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=javatodev&show_icons=true&locale=en" alt="javatodev" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=javatodev&" alt="javatodev" /></p>