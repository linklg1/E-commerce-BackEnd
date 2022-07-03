# E-commerce-BackEnd

## Description
An E-commerce Backend using MySQL, Sequilize, Express, and dotenv. The database allows you to create, retrieve, update and delete data within the generated database.

## Video Link


## Repo

https://github.com/linklg1/E-commerce-BackEnd.git


## Installation
You will need to clone the [Repo](#Repo)

Packages that need installation include: MySQL2, Sequelize, dotenv

You will also need to create a '.env' file with the correct inputs in place you can input the data set provided in .env.EXAMPLE into your .env file and provide your mysql username and password

You will need to run mysql and source the database before running a 'node ./seeds/index.js and then a 'node server.js'


```bash
npm install 

touch .env
```
Edit .env file to include <br />
DB_NAME= 'ecommerce_db'<br />
DB_PASSWORD=`<yourmysqlpassword>`<br />
DB_USER=`<yourmysqlusername>`

```bash
mysql -uroot -p
Enter Password:
source ./db/schema.sql
exit
node ./seeds/index.js
node server.js

```