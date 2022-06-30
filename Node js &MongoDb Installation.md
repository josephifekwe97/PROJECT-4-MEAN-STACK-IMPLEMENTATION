# Install Node.JS

## Update Ubuntu
`sudo apt update`

![sudo update](/PROJECT-4-MEAN-STACK-IMPLEMENTATION/Images/Sudo%20apt%20update.png)

## Upgrade Ubuntu
`sudo apt upgrade`

![sudo upgrade](/PROJECT-4-MEAN-STACK-IMPLEMENTATION/Images/Sudo%20upgrade.png)


## Add Certificate

`sudo apt -y install curl dirmngr apt-transport-https lsb-release ca-certificates`



![Add cert](/PROJECT-4-MEAN-STACK-IMPLEMENTATION/Images/https%20transport%20ca.png)

`curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash-`


![Add cert](/PROJECT-4-MEAN-STACK-IMPLEMENTATION/Images/deb%20nodesources.png)



## Install NodeJs

`sudo apt install -y  nodejs`

![Add cert](/PROJECT-4-MEAN-STACK-IMPLEMENTATION/Images/sudo%20apt%20install%20-y%20nodejs.png)


## Install Mongodb  Process

`sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 0C49F3730359A14518585931BC711F9BA15703C6`

![sudo apt key adv](/PROJECT-4-MEAN-STACK-IMPLEMENTATION/Images/vi%20server1.png)



`echo "deb [ arch=amd64 ] https://repo.mongodb.org/apt/ubuntu trusty/mongodb-org/3.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.4.list`

![echo](/PROJECT-4-MEAN-STACK-IMPLEMENTATION/Images/sudo%20key%20adv.png)


### Install Mongodb

`sudo apt install -y mongodb`

![mongodb Installation](/PROJECT-4-MEAN-STACK-IMPLEMENTATION/Images/sudo%20install%20-y%20mongodb.png)

## Start the server

`sudo service mongodb start`

![mongodb start](/PROJECT-4-MEAN-STACK-IMPLEMENTATION/Images/mongodb%20start.png)



## Verify that the service is up and running **Status

`sudo systemctl status mongodb`

## Install npm – Node package manager.


`sudo apt install -y npm`

![npm install](/PROJECT-4-MEAN-STACK-IMPLEMENTATION/Images/npm%20install.png)




## sudo npm install body-parser
We need ‘body-parser’ package to help us process JSON files passed in requests to the server.

`sudo npm install body-parser`


![body parser](/PROJECT-4-MEAN-STACK-IMPLEMENTATION/Images/npm%20install.png)



## Create a folder named ‘Books’ 
`mkdir Books && cd Books`

![create directory](/PROJECT-4-MEAN-STACK-IMPLEMENTATION/Images/mkdir%20Books.png)


## npm init
`npm init`
![initial project](/PROJECT-4-MEAN-STACK-IMPLEMENTATION/Images/npm%20init.png)


## Add a file to it named server.js

`vi server.js`
![initial project](/PROJECT-4-MEAN-STACK-IMPLEMENTATION/Images/npm%20init.png)

