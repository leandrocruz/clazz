# Clazz

Repositório de código para as aulas que ministro nos cursos de pós-graduação em algumas universidades

## Software

 * [JDK 8 (não o JRE)](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
 * [Maven 3.1.1](https://maven.apache.org/download.cgi)
 * [Git](https://git-scm.com/download/win)
 * [GitHub For Windows](http://windows.github.com)
 * [Mongoose Webserver](https://cesanta.com/mongoose.shtml)
 * [Bower](http://bower.io)

## Instalação

 * Faça a instalação dos pacotes indicados acima
 * Adicione o maven, git e npm (dependência do bower) a variável de ambiente PATH
 * Crie uma conta no github
 * Faça o fork do projeto [class](https://github.com/leandrocruz/clazz)
 * Clone o projeto do seu usuário/branch usando o cliente do github para windows
 * Crie os arquivos de configuração do eclipse com o maven:
  * > cd $PROJETO/design-patters/socialnetwork/server
  * > mvn eclipse:eclipse
 * Importe o projeto no eclipse usando "Import > General > Existing project into workspace"
 * Rode o servidor de aplicações usando o plugin do jetty para o eclipse (no path /api) ou com o maven com o comando mvn jetty:run
 * Instale as dependências do bower:
  * > cd $PROJETO/design-patters/socialnetwork/www
  * > bower install
 * Rode o mogoose, ou outro servidor http, a partir da pasta www

## Git

 * [GitHub Generating SSH Keys](https://help.github.com/articles/generating-ssh-keys/)
 * [Git on Windows](http://guides.beanstalkapp.com/version-control/git-on-windows.html)
 * [ssh-agent problem](https://coderwall.com/p/rdi_wq/fix-could-not-open-a-connection-to-your-authentication-agent-when-using-ssh-add)
 * [password cache](https://help.github.com/articles/caching-your-github-password-in-git/)

## Rest

 * [REST API concepts and examples](https://www.youtube.com/watch?v=7YcW25PHnAA)
 * [Twitter Public API](https://dev.twitter.com/rest/public)
 * [Google Maps Example](http://maps.googleapis.com/maps/api/geocode/json?address=curitiba&sensor=false)
 * [APIGee](https://apigee.com)
 * [Programmable Web](http://www.programmableweb.com/)
 * [Mashape](https://www.mashape.com/)

## Setup
