#MySQL Relational Database

PHP developer's default choice for a relational database, MySQL needs no introduction. With Bluemix, you can easily get a MySQL database with up to 10MB storage and up to 10 connections. 

To try the sample MySQL application, change directory to ```bluemix-mysql-php-sample``` and then deploy to Bluemix by executing the following commands:

```
cf login
cf create-service mysql 100 mySql
cf push
```

After the commands complete successfully, look for the console output specifying the application URL. It should look something like: 

```
usage: 128M x 1 instances
urls: mysql-random-word.mybluemix.net
```

Open your favorite browser using the URL ending with mybluemix.net (such as mysql-random-word.mybluemix.net in the example above) from the console output to access the application. 