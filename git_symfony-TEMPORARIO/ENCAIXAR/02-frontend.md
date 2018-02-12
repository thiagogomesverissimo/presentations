### webpack encore

INSTALAR BOOTSTRAP 4: 

Instalação das bibliotecas de frontend no symfony:

    cd usp
    yarn add @symfony/webpack-encore --dev
    yarn install
    yarn add jquery jquery-ui bootstrap-sass font-awesome-sass sass-loader node-sass

criar:

    cd .assets
    touch js/app.js css/app.scss css/custom.css

Em app.scss:
        
    @import '~bootstrap-sass/assets/stylesheets/bootstrap';
    @import '~font-awesome-sass/assets/stylesheets/font-awesome';


