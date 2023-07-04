Spring Boot Shopping Cart Web App

About:

This is a demo project for practicing Spring + Thymeleaf. The idea was to build some basic shopping cart web app.

It was made using Spring Boot, Spring Security, Thymeleaf, Spring Data JPA, Spring Data REST and Docker. Database is mysql.

There is a login and registration functionality included.

users can shop for products. Each user has his own shopping cart (session functionality). Checkout is transactional

Dummy Database Initialization =================
STEP 1: Open MySQL Command Prompt or MySQL Workbench

STEP 2: Login to the administrator user of MySql: mysql -u <username> -p (Enter Password if asked)

STEP 3: Copy paste and execute the MySQL Query from the following file:-

run the Sql Query From this file: databases/mysql_query.sql

Installation:

git clone https://github.com/RK79719/shopping-cart-1.git
cd shopping-cart-1
docker-compose build

Pre-requisites:

Make sure that you have docker, docker-compose and docker cli installed on the machine.

Run webserver:

docker-compose up
