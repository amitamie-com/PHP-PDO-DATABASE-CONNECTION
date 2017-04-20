# PHP-PDO-DATABASE-CONNECTION

Head to Bootstrap official page, and download a copy. In this project, I have used version 2.3.2.
After that, create a PHP file "index.php".

Below Mysql code I have used to create sample table.

CREATE TABLE  `customers` (
`id` INT NOT NULL AUTO_INCREMENT PRIMARY KEY ,
`name` VARCHAR( 100 ) NOT NULL ,
`email` VARCHAR( 100 ) NOT NULL ,
`mobile` VARCHAR( 100 ) NOT NULL
) ENGINE = INNODB;
