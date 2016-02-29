This is a test repo that will demonstrate my issue with Sequelize: inserting a raw query without an auto-increment primary ID makes it unclear how to get the last inserted ID returned to the user.

Steps to getting this test going:

1. git clone git@github.com:sequelize/sequelize.git
2. npm install
3. mysql -u root -p -h 192.168.99.100 < mydb_tables.sql #insert the right address or localhost for your address
4. node test.js
