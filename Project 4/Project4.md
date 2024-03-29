## Awesome documentation for project 4 - Deploying MEAN Stack Application on Express Server using Ubuntu 20.04 OS

![Project Infrastructure](./images/Project-4.jpg)

`sudo apt update`

![Server Update](./images/sudo-apt-update4.png)

`sudo apt upgrade -y`
![Server Upgrade](./images/sudo-apt-upgrade4.png)


## Add certificates

`sudo apt -y install curl dirmngr apt-transport-https lsb-release ca-certificates`

![Add Certificate](./images/add-certificates.png)
`curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -`

## Install Node
`sudo apt install -y nodejs`

![Install Nodejs](./images/nodejs.png)


## Add Mongo DB Key

`sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 0C49F3730359A14518585931BC711F9BA15703C6`
![MongoDB Key](./images/mongodb-key.png)

## Mongo DB Repository

`echo "deb [ arch=amd64 ] https://repo.mongodb.org/apt/ubuntu trusty/mongodb-org/3.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.4.list`
![MongoDB Repo](./images/mongodb-repo.png)
## Install MongoDB

`sudo apt install -y mongodb`

![Install MongoDB](./images/install-mongo.png)

## Start the Service
`sudo service mongodb start`

![Start MongoDB Service](./images/mongodb-status.png)
## Check the MongoDB Service

`sudo systemctl status mongodb`

![MongoDB Status Service](./images/mongodb-status.png)

## Install Node Package Manager

`sudo apt install -y npm`

![Npm Installation](./images/npm-bodyparser.png)

## Install Body Parser
`sudo npm install body-parser`

![Body Parser Installation](./images/npm-bodyparser.png)

## Initilaize node in the Books directory

`npm init`

![Npm Initialization](./images/npm-init.png)

## Server.Js Content

![Server JS](./images/serverjs.png)

## Install Express.Js and Mongoose

![Express JS Installation](./images/expressjs.png)

## Create a Routes File in the APP.jS Folder

![Routes.js File Creation](./images/routesjs.png)

## Create a Book.JS in the Models Folder

![Book.js file Creation](./images/bookjs.png)

## Create a Script.JS in the public folder

![Script JS File Creation](./images/scriptjs.png)

## Create an Index.html file in the public folder

![Index.Html file creation](./images/indexfile.png)