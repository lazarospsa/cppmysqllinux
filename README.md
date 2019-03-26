# cppmysqllinux
C++ program that connect with mysql with add, edit, delete data. (for Linux)

(Maybe you have to install this)
sudo apt-get install g++ 
sudo apt-get install mysql-server mysql-client
sudo apt-get install libmysql++-dev


(For Compile-Build main.cpp)
g++ -o main -I/usr/include/mysql -I/usr/include/mysql++  -L/usr/lib main.cpp -lmysqlpp -lmysqlclient

For Ubuntu
#include <mysql/mysql.h>
Otherwise
#include <mysql.h>

(MySQL)
I suggest you to use XAMPP for database if you are begginer.

(To run the application)

user@user:~$ cd go_to_directiory/main
user@user:~$ ./main

Instructions:
1) Build the main.cpp
2) Start MySQL server from XAMPP
3) Run the compiled application



IF YOU HAVE PROBLEM!!!

With run application try:
user@user:~$ sudo ./main

With MySQL won't start from XAMPP
-Open Terminal
-type:
sudo service mysql stop
-and then try to start from XAMPP
