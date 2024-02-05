
**Iniciar o serviço docker**
-> `sudo service docker start`

**Rodar no terminal na raiz onde está o projeto**
-> `docker compose up -d`

**Acessar o container do php**
-> `docker compose exec php-fpm bash`

**Instalar o composer do php**
-> https://getcomposer.org/download/
-> `composer install`

**Instalar e configurar o laravel**
-> `composer create-project laravel/laravel:^9.0 example-app`
 > mover os arquivo para a raíz do projeto:

      mv laravel/* .

> gerar a chave laravel: 

    php artisan key:generate
