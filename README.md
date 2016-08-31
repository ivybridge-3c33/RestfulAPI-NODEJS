# RestfulAPI-NODEJS
# create table on mysql server
```sh
CREATE TABLE `tasks` (
  `idtasks` int(11) NOT NULL AUTO_INCREMENT,
  `subject` varchar(255) DEFAULT NULL,
  `description` mediumtext,
  `status` int(1) DEFAULT NULL,
  `createdate` datetime DEFAULT NULL,
  `updatedate` datetime DEFAULT NULL,
  PRIMARY KEY (`idtasks`)
) ENGINE=InnoDB AUTO_INCREMENT=9 DEFAULT CHARSET=utf8;
```
# open server.js and edit MYSQL CONNECTION
on line between 12 to 15
```sh
	host	: 'localhost',
	user	: 'root',
	password: 'qwertyui',
	database: 'task'

```

# run on node js command

```sh
node server.js
```

# test run api using postman
