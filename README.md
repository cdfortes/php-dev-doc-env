# PHP Dev Environment with Docker

A simple way to start php projects with docker.

## Tools
- Docker
- Docker Compose
- Nginx
- PHP 
- MYSQL

## Installation Steps
- Install Docker
- Open a terminal in the folder you want to store your websites
- Clone the repo `git clone https://github.com/cdfortes/php-dev-doc-env` 
- Create a folder `app` on the **root project folder**
- Create a file index.php on the **app folder** with the following content:
    ```php

    <?php

    echo phpinfo();

    ```

- Use `docker-compose up -d`
- Open your browser with the [http://localhost:8081](http://localhost:8081) 
- If everything it's ok will see the php info page
- After that you can create your php projects. To do that you will need create a folder with the name of your project on the app folder.

happy `php` code! :rocket:
