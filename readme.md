# Backup and restore
# install mongodb tools first. Then goto tools install directory where you will find executable files

# To take a back up write 
 ``` mongodump -d DBName Directory ```
``` Example :  mongodump -d TamsDb9 "C:\Users\asus\Pictures" ```

it will have a backup into a folder 

# to restore a database from a directory into mongodb 
 ``` mongorestore -d DBName Directory ```
``` Example : mongorestore -d AmeliaFinalDB2023 D:\APanacea\Tams\DBBackup\AmeliaFinalDB2023 ```
