# whatsapp-meteor

## Crie um novo projeto:

> $ meteor create whatsapp

> $ cd whatsapp
  
## Seu aplicativo agora contém um exemplo ao vivo e pronto. Para executar o nosso aplicativo basta digitar o seguinte na linha de comando:
  
  > $ meteor
  
## Nós também podemos executar o nosso aplicativo dentro do simulador iOS ou emulador Android, só precisamos adicionar a plataforma para Meteor vai construir o projeto para a nova plataforma:

> $ meteor add-platform ios

ou caso queira <b>Android</b>

> $ meteor add-platform android

## Para remover os arquivos desnecessários basta fazer isso aqui:

> rm -rf server client

## Em seguida, substituiremos o Blaze para usarmos AngularJS:

> $ meteor remove blaze-html-templates

> $ meteor add angular-templates

## Também precisamos ter certeza de que o Ionic está instalado junto com suas dependências:

> $ meteor add dab0mb:ionic-assets

> $ meteor npm install angular@^1.5.8 --save

> $ meteor npm install angular-animate@^1.5.8 --save

> $ meteor npm install angular-sanitize@^1.5.8 --save

> $ meteor npm install angular-ui-router@^0.3.1 --save

> $ meteor npm install ionic-scripts --save

> $ meteor npm install babel-runtime --save

Se você for um usuário do iOS, poderá encontrar alguns problemas relacionados ao toque duplo não sendo enviado corretamente. Isso é causado devido a um pacote incluído automaticamente pelo <b>Meteor</b> e é chamado de <b>mobile-experience</b> para que possamos ter um sentimento mais nativo para o nosso aplicativo, uma vez executado em um dispositivo móvel, que nem sempre é direito em toda a placa. Este pacote é simplesmente um cluster dos seguintes pacotes:

* **Fastclick** - Evite o atraso de toque de 300ms.
* **Mobile-status-bar** - Evite as informações da barra de status que cobrem o conteúdo do seu aplicativo.
* **Tela de lançamento** - Cubra o aplicativo com uma imagem de lançamento para que as pessoas não tenham que ver as coisas carregando.

Você já pode descobrir que o <b>fastclick</b> é uma base potencial para o nosso problema. Assim, vamos instalar os mesmos pacotes de <b>mobile-experience</b> nos fornece, com a exceção de <b>fastclick</b>:

> meteor add mobile-status-bar

> meteor add launch-screen

E, finalmente, vamos instalar angular-meteor, de que este tutorial é toda sobre:

> meteor npm install angular-meteor --save

#### CONTINUA....
  
