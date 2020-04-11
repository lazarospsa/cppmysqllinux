# cppmysqllinux

<a href="https://paypal.me/lazarospsarokostas" rel="nofollow"><img src="https://camo.githubusercontent.com/d5d24e33e2f4b6fe53987419a21b203c03789a8f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f446f6e6174652d50617950616c2d677265656e2e737667" alt="Donate" data-canonical-src="https://img.shields.io/badge/Donate-PayPal-green.svg" style="max-width:100%;"></a>

Database MySQL Connectivity using C++ (for Linux)

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
user@user:~$ cd go_to_directiory/main
user@user:~$ ./main
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

Performance
```
100 MySQL records -> exec -> Time taken: 0.02717200s
```

