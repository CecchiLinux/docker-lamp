# docker-lamp

Run a LAMP server ready to use with Apache2, PHP7, MySQL e phpMyAdmin.



## Obtain and start the LAMP server

```bash
git clone https://github.com/CecchiLinux/docker-lamp.git
cd docker-lamp
docker-compose up -d
```

Visit `http://localhost:80` to view the website.

You have to see a message that confirm the database connection and the phpinfo page.



## Use phpMyAdmin

Visit `localhost:8081`

* username: `root`
* password: `password`



## More info

* **php docker image**: `php:7-apache`
* **mysql docker image**:  `mysql:5.7`
* **phpmyadmin image**: `phpmyadmin/phpmyadmin` (latest)



