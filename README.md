![GitHub Logo](https://s3.ap-south-1.amazonaws.com/greyatom-social/GreyAtom-logo.png)

# Overview

MySQL is a common open source relational database for creating, reading, updating and deleting data in Python web applications. This repository contains instructions about how to set up a mysql-workbench environment on ubnutu 16.04. All the testing in GreyAtom IDE will be done against this configuration. It sets up the following packages:

* MySQL
* MySQL-Workbench

# Setting up your system for MySQL development

## Prerequisites
The instructions have been tested only on Ubuntu and OS X. Please go through this link to setup your environment.

1. Ubuntu 16.04 OR
2. Mac

## Install MySQL

Download latest version of MySQL and install on your machine.

|        | Linux | Mac |
|--------|-------|-----|
| 64-bit | [Ubuntu64](https://dev.mysql.com/get/Downloads/MySQL-5.7/mysql-server_5.7.18-1ubuntu16.04_amd64.deb-bundle.tar) | [mac64](https://dev.mysql.com/get/Downloads/MySQL-5.7/mysql-5.7.18-macos10.12-x86_64.dmg) |
| 32-bit | [Ubuntu32](https://dev.mysql.com/get/Downloads/MySQL-5.7/mysql-server_5.7.18-1ubuntu16.04_i386.deb-bundle.tar)| |

Once you downloaded it for ubnutu you can untar file and install mysql server and client. Installation of client is optional as we are going to connect with MySQL Workbench. While installing MySQL remember:
* Set host name as 127.0.0.1 / Localhost
* Use port 3306
* Username root
* Setup password for root and remember

After installation is complete we can move ahead to install MySQL Workbench.

## Install MySQL Workbench

Download latest version of MySQL-Workbench and install on your machine.

|        | Linux | Mac |
|--------|-------|-----|
| 64-bit | [Ubuntu64](https://dev.mysql.com/get/Downloads/MySQLGUITools/mysql-workbench-community-6.3.9-1ubuntu16.04-amd64.deb) | [mac64](https://dev.mysql.com/get/Downloads/MySQLGUITools/mysql-workbench-community-6.3.9-osx-x86_64.dmg) |
| 32-bit | [Ubuntu32](https://dev.mysql.com/get/Downloads/MySQLGUITools/mysql-workbench-community-6.3.9-1ubuntu16.04-amd64.deb)| |

## Configure Workbench to work with MySQL

To add a connection, click the [+] icon to the right of the MySQL Connections title on the home screen. This opens the Setup New Connection form:

![Image of New MySQL Connection](https://s3.ap-south-1.amazonaws.com/greyatom-social/wb-mysql-connections-setup-new-connection.png)

Use Vault to store your root user password. If you have created different user than root please specify accordingly.

Test your connection!

Once your connection is successful you can download SQL resource files from [here](https://github.com/commit-live-students/sql-resources).
