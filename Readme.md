Install:

1. MongoDB
2. Node (including NPM)
3. Visual Studio Code
4. Git

# MongoDB

[reference](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/)

```bash

sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 9DA31620334BD75D9DCB49F368818C72E52529D4

echo "deb [ arch=amd64 ] https://repo.mongodb.org/apt/ubuntu bionic/mongodb-org/4.0 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-4.0.list

sudo apt-get update

sudo service mongod start

mongo

show dbs

exit

```

# Node

[reference](https://github.com/nodesource/distributions/blob/master/README.md)

```bash

sudo apt install curl

curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -

sudo apt-get install -y nodejs

```

# Visual Studio Code

From Ubuntu Software Center
