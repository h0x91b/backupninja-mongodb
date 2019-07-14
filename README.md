[MongoDB"](http://www.mongodb.org/): database backup handler for [backupninja](https://labs.riseup.net/code/projects/show/backupninja)

Performs binary backup (using `mongodump` utility) of MongoDB database.

Installation instructions
===

You will need to install

* backupninja
* cUrl

Copy [mongodd.helper](https://raw.githubusercontent.com/h0x91b/backupninja-mongodb/master/mongodb.helper) into `/usr/share/backupninja/mongodb.helper`

    curl -L https://raw.githubusercontent.com/h0x91b/backupninja-mongodb/master/mongodb.helper > /usr/share/backupninja/mongodb.helper

Copy [mongodd](https://raw.githubusercontent.com/h0x91b/backupninja-mongodb/master/mongodb) into `/usr/share/backupninja/mongodb`

    curl -L https://raw.githubusercontent.com/h0x91b/backupninja-mongodb/master/mongodb > /usr/share/backupninja/mongodb

Then you can run `ninjahelper`, you will see new submenu.

    ninjahelper

