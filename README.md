# Lambda School Web API: Java Course 
## Software installations for Week 1 

<details><summary>For All Operating Systems</summary>
<p>

### To be done after installing the software for your specific operating system

[![Video to Install JDK](http://img.youtube.com/vi/OswS2dkvjnU/0.jpg)](http://www.youtube.com/watch?v=OswS2dkvjnU)

The Jet Brains IntelliJ IDEA Ultimate Version is installed from your GitHub Student Package. We do need the Ultimate Version for the class. When installing, taking the defaults is the best way to proceed.

This video shows how your instructor has configured his IDE. You may have your own preferences.

Some notes on configuration:

* Under Code Folding, only the show Code Folding Menu should be checked
* All Braces placement should say Next Line
* All places should say Force Braces
* Only Annotations should be wrapped
* Remember to connect your GitHub profile to IntelliJ

</p>
</details>


<details><summary>For Windows 10 Operating System</summary>
<p>

### Install JDK Version 11 on a Windows 10 based computer

[![Video to Install JDK](http://img.youtube.com/vi/XQfRnglIcYE/0.jpg)](http://www.youtube.com/watch?v=XQfRnglIcYE)

The basic steps to installing the software are:

* Download and install the Windows software from:  
[https://www.oracle.com/technetwork/java/javase/downloads/jdk11-downloads-5066655.html](https://www.oracle.com/technetwork/java/javase/downloads/jdk11-downloads-5066655.html)

Note that you have to accept the licensing agreement before you can download the software
* add to environment variable JAVA_HOME C:\Program Files\Java\jdk-11.0.2
* add to path C:\Program Files\Java\jdk-11.0.2\bin

To test the installation
* java -version
* javac -version

---
### Install the Sublime Text Editor on a Windows 10 based computer

[![Video to Install Sublime](http://img.youtube.com/vi/Rk6sm0i2luE/0.jpg)](http://www.youtube.com/watch?v=Rk6sm0i2luE)

Download and install the Windows software from
[https://www.sublimetext.com/](https://www.sublimetext.com/)

---
### Install Git Bash on a Windows 10 based computer

[![Video to Install Git Bash](http://img.youtube.com/vi/QElJOX2wdfc/0.jpg)](http://www.youtube.com/watch?v=QElJOX2wdfc)

Surf to the site [https://gitforwindows.org/](https://gitforwindows.org/)

Download and install the software

To configure Git, enter the following from a command prompt
* git config --global user.name " < Your Name > "
* git config --global user.name " < Your GitHub email address > "

---
### Install PostgreSQL on a Windows 10 based computer

[![Video to Install PostgreSQL](http://img.youtube.com/vi/y1DV86i9vDY/0.jpg)](http://www.youtube.com/watch?v=y1DV86i9vDY)

* Download and install the software from [https://www.enterprisedb.com/downloads/postgres-postgresql-downloads](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads)
* Install all the available software from the download. At the end, you do not need to launch Stack Builder at this time.
* You must restart your machine after this install.

---
### Install Postman on a Windows 10 based computer

[![Video to Install Postman](http://img.youtube.com/vi/q-cw1IVvgzQ/0.jpg)](http://www.youtube.com/watch?v=q-cw1IVvgzQ)

Download and install the software from [https://www.getpostman.com/](https://www.getpostman.com/)

---
### Install Heroku CLI on a Windows 10 based computer

[![Video to Install Heroku CLI](http://img.youtube.com/vi/s6QI9rHUd9E/0.jpg)](http://www.youtube.com/watch?v=s6QI9rHUd9E)

* Create a free Heroku Account at [https://www.heroku.com](https://www.heroku.com)
* Download and install the Heroku CLI software from [https://devcenter.heroku.com/articles/heroku-cli](https://devcenter.heroku.com/articles/heroku-cli)
* To test, from a command prompt type
```heroku login```

---
### Install Tomcat on a Windows 10 based computer

[![Video to Install Tomcat](http://img.youtube.com/vi/ujTiDoTkcQ4/0.jpg)](http://www.youtube.com/watch?v=ujTiDoTkcQ4)

* Download and install the software from [https://tomcat.apache.org/download-90.cgi](https://tomcat.apache.org/download-90.cgi)
* Tomcat by default installs as a Windows Service running on port 8080
* To test surf to localhost:8080 and see the Tomcat opening page appear

---
### *** OPTIONALLY *** Install RabbitMQ on a Windows 10 based computer

[![Video to Install RabbitMQ](http://img.youtube.com/vi/EjSuWP7m0kk/0.jpg)](http://www.youtube.com/watch?v=EjSuWP7m0kk)

Install the Erlang software. RabbitMQ requires this development system to be installed first:
* Surf to [http://www.erlang.org/downloads](http://www.erlang.org/downloads)
* Download the 64 bit software for Windows
* Install the software as an Administrator

Now install the actual RabbitMQ Server
* Surf to [https://www.rabbitmq.com/install-windows.html](https://www.rabbitmq.com/install-windows.html) and install the software
* Add the RabbitMQ installation directory to your path
* Test by running from the command prompt: rabbitmqctl version. You should get a response showing the version of rabbitmq installed.

---
### *** OPTIONALLY *** Install Redis on a Windows 10 based computer

[![Video to Install Redis](http://img.youtube.com/vi/EjSuWP7m0kk/0.jpg)](http://www.youtube.com/watch?v=EjSuWP7m0kk)

Redis only runs on Linux. In order to run a Windows 10 based computer, a Linux subsystem must first be installed.
* Verify that the Windows 10 version is greater than 1709 by running winver from a command prompt. If the Windows version is less than 1709, upgrade the system. The upgrade is available free from Microsoft through the Windows Update Process.
* From a Powershell prompt being run as Administrator, enable a Linux subsystem with the command: 
Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
* Surf to [https://www.microsoft.com/en-us/p/ubuntu-1804/9n9tngvndl3q](https://www.microsoft.com/en-us/p/ubuntu-1804/9n9tngvndl3q)
* Download and install the Ubuntu 18 subsystem. Ubuntu is a version of Linux

After launching the subsystem, run the following commands to install Redis
* sudo apt-get update
* sudo apt-get upgrade
* sudo apt-get install redis-server
* sudo service redis-server restart

To verify the installation:
* from a command prompt, run redis-cli -v  
This should return the version of Redis installed on the computer.
* from a command prompt, run redis-cli ping  
Redis should respond with pong

---
</p>
</details>


<details><summary>For Mac OS</summary>
<p>

### Install Homebrew on a Mac OS computer

[![Video to Install Homebrew](http://img.youtube.com/vi/51jnG_-_7tE/0.jpg)](http://www.youtube.com/watch?v=51jnG_-_7tE)

To install Homebrew, first install the Xcode CLI. Alternatively, install the full Xcode software provided by Apple.
* To install the Xcode cli, from a terminal prompt enter  
```xcode-select --install```
* To install Homebrew, from a terminal prompt enter  
```ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"```
* To test the Homebrew installation, from a terminal prompt enter  
```brew doctor```

---
### Install JDK 11 on a Mac OS computer

[![Video to Install JDK 11](http://img.youtube.com/vi/SEhvkT_eQ5k/0.jpg)](http://www.youtube.com/watch?v=SEhvkT_eQ5k)

Download and install the dmg software from [https://www.oracle.com/technetwork/java/javase/downloads/jdk11-downloads-5066655.html](https://www.oracle.com/technetwork/java/javase/downloads/jdk11-downloads-5066655.html)
In order to download the software, first accept the licensing agreement.

To configure the software
* determine the java home path. From a terminal prompt enter  
```/usr/libexec/java_home -v11```
* Go to your home directory. Enter  
```cd``` 
* Edit your user profile. Enter  
```nano .bash_profile```
* At the end of the file, add  
```export JAVA_HOME="<directory found earlier>"```
* Exit nano and restart your computer.

To test the software, from a terminal prompt enter
* java -version
* javac -version
both should respond with version numbers

---
### Install Sublime Text edit on a Mac OS Computer

[![Video to Install Sublime](http://img.youtube.com/vi/XvgrHxmNsvQ/0.jpg)](http://www.youtube.com/watch?v=XvgrHxmNsvQ)

Surf to the website [https://www.sublimetext.com/](https://www.sublimetext.com/) and install the software

---
### Install PostgreSQL on a Mac OS Computer

[![Video to Install PostgreSQL](http://img.youtube.com/vi/JU7rIkXyQYs/0.jpg)](http://www.youtube.com/watch?v=JU7rIkXyQYs)

* Download and install the software from [https://www.enterprisedb.com/downloads/postgres-postgresql-downloads](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads)
* Install all the available software from the download. At the end, you do not need to launch Stack Builder at this time.
* You must restart your machine after this install.

NOTE:

If you run into issues, try entering the following command in a terminal window. Then try to reinstall!  
```sudo spctl --master-disable```

---
### Install Postman on a Mac OS Computer

[![Video to Install Postman](http://img.youtube.com/vi/PSrRNnZgLXI/0.jpg)](http://www.youtube.com/watch?v=PSrRNnZgLXI)

Surf to the website [https://www.getpostman.com/](https://www.getpostman.com/) and install the software</p>

---
### Install Heroku CLI on a Mac OS Computer

[![Video to Install Heroku CLI](http://img.youtube.com/vi/ty5xkk-P8qs/0.jpg)](http://www.youtube.com/watch?v=ty5xkk-P8qs)

Create a free Heroku account at the website [https://www.heroku.com](https://www.heroku.com)

Install the Heroku CLI. At a terminal prompt, enter  
```brew tap heroku/brew && brew install heroku```

Test Heroku by entering a terminal prompt  
``heroku login``

---
### Install Tomcat on a Mac OS Computer

[![Video to Install Tomcat](http://img.youtube.com/vi/vM0TDbm09LM/0.jpg)](http://www.youtube.com/watch?v=tvM0TDbm09LM)

To install the software
* brew install tomcat
* brew services start tomcat
The configuration file can be found at  
```/usr/local/Cellar/tomcat/9.0.17/libexec/conf```

---
### *** OPTIONALLY *** Install RabbitMQ on a Mac OS Computer

[![Video to Install RabbitMQ](http://img.youtube.com/vi/KygNhA0-VQk/0.jpg)](http://www.youtube.com/watch?v=KygNhA0-VQk)

Using Homebrew from a terminal prompt, enter
* brew update
* brew install rabbitmq

* Go to your home directory. Enter  
```cd ```
* Edit your user profile. Enter  
```nano .bash_profile```
* At the end of the file, add  
```export PATH=$PATH:/usr/local/opt/rabbitmq/sbin```
* Exit nano and restart your computer.  
* After machine has restarted and from a terminal prompt, enter  
```brew services start rabbitmq```

To test RabbitMQ, from a terminal prompt enter  
```rabbitmqctl version```  
A version number should be the response.

NOTE:

If you are still having trouble running rabbitmqctl, try adding another export PATH statement to your .bash_profile  
```export PATH=$PATH:/usr/local/sbin```

---
### *** OPTIONALLY *** Install Redis on a Mac OS Computer

[![Video to Install Redis](http://img.youtube.com/vi/8o8CWZTb1j0/0.jpg)](http://www.youtube.com/watch?v=8o8CWZTb1j0)

Using Homebrew from a terminal prompt enter
* brew update
* brew install redis
* brew services start redis

To test the installation from a terminal prompt enter
* redis-cli ping   
Redis will respond with pong

---
</details>


<details><summary>For Linux specifically Ubuntu 18</summary>
<p>
  
### Install JDK Version 11 on a Linux Computer

[![Video to Install JDK](http://img.youtube.com/vi/LRBot07vRsU/0.jpg)](http://www.youtube.com/watch?v=LRBot07vRsU)

From a terminal prompt, enter 
* sudo add-apt-repository ppa:linuxuprising/java
* sudo apt update
* sudo apt install oracle-java11-installer
* sudo apt install oracle-java11-set-default

To test the installation, enter
* java -version
* javac -version   
Both should respond with version numbers

---
### Install Sublime Text Editor on a Linux Computer

[![Video to Install Sublime](http://img.youtube.com/vi/SgdmgSasU30/0.jpg)](http://www.youtube.com/watch?v=SgdmgSasU30)

From a terminal prompt, enter 
* wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
* echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list
* sudo apt update
* sudo apt install sublime-text

---
### Install Git on a Linux Computer

[![Video to Install Git](http://img.youtube.com/vi/3kh_c9Os_z4/0.jpg)](http://www.youtube.com/watch?v=3kh_c9Os_z4)

From a terminal prompt, enter
* sudo apt upgrade
* sudo apt install git

To configure Git, enter the following from a terminal prompt
* git config --global user.name " < Your Name > "
* git config --global user.name " < Your GitHub email address > "

---
### Install PostgreSQL on a Linux Computer

[![Video to Install PostgreSQL](http://img.youtube.com/vi/XuiaSJAVtNo/0.jpg)](http://www.youtube.com/watch?v=XuiaSJAVtNo)

To install PostgreSQL, enter the following from a terminal prompt

* sudo nano /etc/apt/sources.list.d/pgdg.list
** enter the following line   
```deb http://apt.postgresql.org/pub/repos/apt/ bionic-pgdg main```   
** exit nano
* wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add -
* sudo apt update
* sudo apt install postgresql-11
* sudo apt install postgresql-client-11
* sudo apt install pgadmin4

* sudo -u postgres psql
* ALTER USER postgres PASSWORD 'password';
* \q

* run pgadmin4 from APPs   
Create a link to the server</p>

---
### Install Postman on a Linux Computer

[![Video to Install Postman](http://img.youtube.com/vi/4yMn6h0_MGI/0.jpg)](http://www.youtube.com/watch?v=4yMn6h0_MGI)

To install Postman, from a terminal prompt enter
* sudo apt update
* sudo apt install libgconf-2-4

Surf to the website [https://getpostman.com](https://getpostman.com)
* Download the software in a compressed file
* Extract the file to some location, like your home directory

Create a Desktop entry for Postman. It should be saved as   
```~/.local/share/applications/Postman.desktop```   
and contain the following

```
[Desktop Entry]
Encoding=UTF-8
Name=Postman
Exec=/home/<your account>/Postman/app/Postman %U
Icon=/home/<your account>/Postman/app/resources/app/assets/icon.png
Terminal=false
Type=Application
Categories=Development;
```

---
### Install Heroku CLI on a Linux Computer

[![Video to Install Heroku CLI](http://img.youtube.com/vi/6Wm2Oo2ixXI/0.jpg)](http://www.youtube.com/watch?v=6Wm2Oo2ixXI)

Create a free Heroku account at the website https://www.heroku.com

Install the Heroku CLI. At a terminal prompt, enter    
```sudo snap install --classic heroku```

Test Heroku by entering a terminal prompt   
```heroku login```

---
### Install Tomcat on a Linux Computer

[![Video to Install Tomcat](http://img.youtube.com/vi/PbFgS2SfaZE/0.jpg)](http://www.youtube.com/watch?v=PbFgS2SfaZE)

To install Apache Tomcat, enter the following from a terminal prompt:

* sudo groupadd tomcat
* sudo useradd -s /bin/false -g tomcat -d /opt/tomcat tomcat
* cd /opt/
* sudo wget http://apache.cs.utah.edu/tomcat/tomcat-9/v9.0.17/bin/apache-tomcat-9.0.17.tar.gz
* sudo tar -xzvf apache-tomcat-9.0.17.tar.gz
* sudo mv apache-tomcat-9.0.17/ tomcat/
* sudo chown -hR tomcat:tomcat /opt/tomcat
* sudo chmod +x /opt/tomcat/bin/
* sudo nano ~/.bashrc
  * Add the following line   
```export CATALINA_HOME=/opt/tomcat```
  * exit nano

* source ~/.bashrc
* echo $CATALINA_HOME   
You should see /opt/tomcat

* cd /etc/systemd/system/
* sudo nano apache-tomcat.service
  * enter the following 18 lines
```
[Unit]
Description=Apache Tomcat 9 Servlet Container
After=syslog.target network.target

[Service]
User=tomcat
Group=tomcat
Type=forking
Environment=JAVA_HOME=/usr/lib/jvm/java-11-oracle
Environment=CATALINA_PID=/opt/tomcat/tomcat.pid
Environment=CATALINA_HOME=/opt/tomcat
Environment=CATALINA_BASE=/opt/tomcat
ExecStart=/opt/tomcat/bin/startup.sh
ExecStop=/opt/tomcat/bin/shutdown.sh
Restart=on-failure

[Install]
WantedBy=multi-user.target
```
  * exit nano

* sudo chown -hR tomcat:tomcat /opt/tomcat
* sudo chmod +x /opt/tomcat/bin/

* systemctl daemon-reload
* systemctl start apache-tomcat
* systemctl enable apache-tomcat

To test Tomcat, surf to localhost:8080
* You should see the Tomcat default webpage
* Tomcat defaults to listening on port 8080

---
### *** OPTIONALLY *** Install RabbitMQ on a Linux Computer

[![Video to Install RabbitMQ](http://img.youtube.com/vi/jDPsisgWpr0/0.jpg)](http://www.youtube.com/watch?v=jDPsisgWpr0)

To install the software, first install Erlang and then the RabbitMQ server by doing the following from a terminal prompt:

* sudo apt update
* sudo apt install curl
* wget -O - "https://github.com/rabbitmq/signing-keys/releases/download/2.0/rabbitmq-release-signing-key.asc" | sudo apt-key add -
* sudo apt install apt-transport-https
* sudo nano /etc/apt/sources.list.d/bintray.erlang.list
  * Add the line   
```deb http://dl.bintray.com/rabbitmq-erlang/debian bionic erlang```
  * exit nano
* sudo apt update
* sudo apt install erlang-nox
* sudo nano /etc/apt/preferences.d/erlang
  * Add the three lines   
```
Package: erlang*
Pin: release o=Bintray
Pin-Priority: 1000
```
  * exit nano
* sudo apt update
* sudo apt-cache policy
* curl -s https://packagecloud.io/install/repositories/rabbitmq/rabbitmq-server/script.deb.sh | sudo bash
* sudo apt update
* sudo apt install rabbitmq-server
* sudo service rabbitmq-server start

Test the installation by entering the following at a terminal prompt
* sudo rabbitmqctl version
RabbitMQ should respond with a version number

---
### *** OPTIONALLY *** Install Redis on a Linux Computer

[![Video to Install Redis](http://img.youtube.com/vi/wWRxgPFO1zE/0.jpg)](http://www.youtube.com/watch?v=wWRxgPFO1zE)

To install Redis, enter the following at a terminal prompt

* sudo apt update
* sudo apt install redis-server
* sudo nano /etc/redis/redis.conf
  * search for supervised change line to supervised systemd
  * exit nano
* sudo systemctl restart redis.service

To test Redis, enter the following at a terminal prompt
* redis-cli ping   
Redis will respond with pong

---
</p>
</details>
