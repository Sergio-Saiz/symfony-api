# symfony-api con Api Platform, Rabbit MQ y Docker

Swwagger (api_plattform): 
http://localhost:250/api/v1/docs

Una vez levantado los contenedores de api, ejecutar en el contenedor be:

composer update

php bin/console doctrine:database:create

php bin/console doctrine:migrations:migrate

php bin/console lexik:jwt:generate-keypair

Mailcatcher:
http://localhost:1080/

RabbitMQ
http://localhost:15672/
es necesario archivo importar configuracion de rabbitmq 

