# Symfony-NDMA

## To run this project

### 1. Clone the project
> git clone https://github.com/ErwanBennic/Symfony-NDMA.git

### 2. Update dependencies
> composer install

### 3. Start server
> symfony server:start

**Symfony version :** 5.0.8  
**Recommanded PHP version :** > 7.2.10


### Usefull commands  

Starts the web server in background  
> symfony serve -d  

List all running web servers  
> symfony server:list

Display web server status 
> symfony server:status

Load fixtures
> php bin/console doctrine:fixtures:load

List of commands
> php bin/console list 

Start listening to mqtt messages
> php bin/console mqtt:listen


If you get CORS issues, you will need this chrome extension.  
> https://chrome.google.com/webstore/detail/cors-unblock/lfhmikememgdcahcdlaciloancbhjino/related
