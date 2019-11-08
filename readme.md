This is an example of RESTful CRUD in Node.js n mySQL.


## NodeJS Installation
*for newbies : Clone or download zip to your machine then hit this :

    cd <working-dir>/rest-crud

then

    npm install
    /usr/bin/node server.js

## Mysql

Seed data : https://cxlshare.s3.us-east-2.amazonaws.com/artifacts/mysql/mysqlAndNodejs.sql


## Configuration (database)
server.js

        host : process.env.MySql_privateIP,
        user : process.env.MySql_dbUserName,
        password : process.env.MySql_dbPassword,
        port : 3306, //port mysql
        database : process.env.MySql_dbName,	





## Open your Browser

    And type: http://<ip-address>:3000/
