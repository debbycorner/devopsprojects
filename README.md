*Logged into AWS account and created a key pair for Beanstalk instance

*Created security group for backend services, Elasticache, RDS, and Active MQ

*Created RDS, ElastiCache, and Amazon Active MQ

*Created Elastic Beanstalk environment

*Updated backend security group to allow traffic from Beanstalk security group

*Updated backend security group to allow internal traffic for backend services to interact with each other

*Launched EC2 instance and initialized RDS database through MySQL login

### Prerequisites
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

### Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
### Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql


