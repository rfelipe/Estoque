# Passo a Passo para instalar a base

1. Copiar ou clonar todos os arquivos deste repositório 
2. composer install 
3. Criar o banco de dados 
4. Configurar o arquivo .env 
5. php artisan key:generate 
6. php artisan migrate 
7. php artisan db:seed 


### caso tenha erro ao rodar o composer
composer config -g -- disable-tls false 

# Executar:
php artisan serve
Abra o navegador em localhost:8000

# Executar API: