# whatsapp-meteor

* Crie um novo projeto

> $ meteor create whatsapp

> $ cd whatsapp
  
 * Seu aplicativo agora contém um exemplo ao vivo e pronto. Para executar o nosso aplicativo basta digitar o seguinte na linha de comando
  
  > $ meteor
  
* Nós também podemos executar o nosso aplicativo dentro do simulador iOS ou emulador Android, só precisamos adicionar a plataforma para Meteor vai construir o projeto para a nova plataforma:

> $ meteor add-platform ios

ou caso queira <b>Android</b>

> $ meteor add-platform android

* Para remover os arquivos desnecessários basta fazer isso aqui:

> rm -rf server client

* Em seguida, substituiremos o Blaze para usarmos AngularJS:

> $ meteor remove blaze-html-templates

> $ meteor add angular-templates

* Também precisamos ter certeza de que o Ionic está instalado junto com suas dependências:

> $ meteor add dab0mb:ionic-assets

> $ meteor npm install angular@^1.5.8 --save

> $ meteor npm install angular-animate@^1.5.8 --save

> $ meteor npm install angular-sanitize@^1.5.8 --save

> $ meteor npm install angular-ui-router@^0.3.1 --save

> $ meteor npm install ionic-scripts --save

> $ meteor npm install babel-runtime --save


#### CONTINUA....
  
