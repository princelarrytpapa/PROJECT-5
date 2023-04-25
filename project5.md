## PROJECT 5: Client/Server Architecture Using A MySQL Relational Database Management System

#Cloning github for project 5
git clone git@github.com:princelarrytpapa/PROJECT-5.git

#Create and configure two Linux-based virtual servers (EC2 instances in AWS)
Server
Client

## SERVER
 sudo apt update
 sudo apt install mysql-server -y
 sudo systemctl enable mysql
 sudo mysql
 sudo systemctl restart mysql
 ip addr show
 sudo vi /etc/mysql/mysql.conf.d/mysqld.cnf
 sudo systemctl restart mysql

## CLIENT
sudo apt update
sudo apt install mysql-client -y
ip addr show
sudo mysql -u remote_user -h 172.31.87.34 -p

  

