# cppmysqllinux
Database MySQL Connectivity using C++ (for Linux)
![C++](https://sdtimes.com/wp-content/uploads/2018/03/cpppp-490x490.png)
![MySQL](https://cdn.freebiesupply.com/logos/large/2x/mysql-logo-png-transparent.png)

(Maybe you have to install this)
```
sudo apt-get install g++ 
sudo apt-get install mysql-server mysql-client
sudo apt-get install libmysql++-dev
```

(For Compile-Build main.cpp)
```
g++ -o main -I/usr/include/mysql -I/usr/include/mysql++  -L/usr/lib main.cpp -lmysqlpp -lmysqlclient
```

For Ubuntu
```
#include <mysql/mysql.h>
```
Otherwise
```
#include <mysql.h>
```

(MySQL)
I suggest you to use XAMPP for database if you are begginer.

(To run the application)
```
user@user: cd go_to_directiory/main
user@user: ./main
```

Instructions:
1) Build the main.cpp
2) Start MySQL server from XAMPP
3) Run the compiled application



IF YOU HAVE PROBLEM!!!

With run application try:
```
user@user:~$ sudo ./main
```
With MySQL won't start from XAMPP

-Open Terminal

-type:
```
sudo service mysql stop
```
-and then try to start from XAMPP
