# 1. sudo apt update

# 2. sudo apt install nginx

# 3. sudo systemctl status nginx

# 4. curl http://localhost:80

# 5. [localhost.png](https://github.com/Lummysloane/Project-2/blob/main/localhost.png)

# 6. [Nginx.png](https://github.com/Lummysloane/Project-2/blob/main/Nginx.png)

# 7. sudo apt install mysql-server

# 8. sudo mysql

# 9. [mysql.png](https://github.com/Lummysloane/Project-2/blob/main/mysql.png)

# 10. sudo mysql -p

# 11. [mysql -p.png](https://github.com/Lummysloane/Project-2/blob/main/mysql%20-p.png)

# 12. sudo apt install php-fpm php-mysql

# 13. [nginx-php.png](https://github.com/Lummysloane/Project-2/blob/main/nginx-php.png)

# 14. sudo mkdir /var/www/projectLEMP

# 15. sudo chown -R $USER:$USER /var/www/projectLEMP

# 16. sudo nano /etc/nginx/sites-available/projectLEMP

# 17. sudo ln -s /etc/nginx/sites-available/projectLEMP /etc/nginx/sites-enabled/

# 18. sudo nginx -t

# 19. [projectLEMP.png](https://github.com/Lummysloane/Project-2/blob/main/projectLEMP.png)

# 20 sudo systemctl reload nginx

# 21 sudo echo 'Hello LEMP from hostname' $(curl -s http://169.254.169.254/latest/meta-data/public-hostname) 'with public IP' $(curl -s http://169.254.169.254/latest/meta-data/public-ipv4) > /var/www/projectLEMP/index.html

# 22. [Hellolemp.png](https://github.com/Lummysloane/Project-2/blob/main/HelloLEMP.png)

# 23. sudo nano /var/www/projectLEMP/info.php

# 24. <?php
phpinfo();

[phpversion.png](
