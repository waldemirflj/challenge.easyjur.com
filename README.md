# challenge.easyjur.com

> Projeto utilizando Laravel Framework 10 (v10.48.10), Laradock e PHP v8.3.6.

### Ambiente de desenvolvimento com Laradock

```bash
    # No terminal de sua preferência, execute o comando a seguir.
    git clone https://github.com/laradock/laradock.git laradock
    
    
    # Na raiz do projeto (laradock), execute o comando a seguir.
    cd  /home/waldemir/www/laradock/
    cp /home/waldemir/www/laradock/.env.example /home/waldemir/www/laradock/.env

    # Iniciando o ambiente de desenvolvimento
    docker compose up nginx workspace

    # Desligando o ambiente de desenvolvimento
    docker compose down -v

    # Acessando o ambiente de desenvolvimento (não necessário)
    # docker compose exec -it --user=laradock workspace bash

    # Criando o projeto a partir do ambiente de desenvolvimento (não necessário)
    # composer create-project laravel/laravel /var/www/challenge.easyjur.com/webserver "10.*" --prefer-dist

    # Configurando o caminho do seu projeto no seu ambiente
    code /home/waldemir/www/laradock/.env

    # De: APP_CODE_PATH_HOST=../
    # Para:  APP_CODE_PATH_HOST=/home/waldemir/www/challenge.easyjur.com/webserver
```

### Projeto (webserver)
```bash
    # Na raiz do projeto (webserver), execute o comando a seguir.
    cd /home/waldemir/www/challenge.easyjur.com/webserver
    chmod -R 777 storage/logs
```

### Dependências & Tecnologias
- [PHP](https://www.php.net/)
- [MySQL](https://www.mysql.com/)
- [Composer](https://getcomposer.org/)
- [Laradock](https://laradock.io/)
- [Docker & Docker compose](https://docs.docker.com/desktop/install/linux-install/)



