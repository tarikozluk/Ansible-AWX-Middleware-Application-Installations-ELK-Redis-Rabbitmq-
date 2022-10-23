# Middleware Applications and Installations with Ansible AWX (Automated Systems)

### Elasticsearch, Logstash, Kibana, Curator Installation
To install ELK Stack, create a new project in Ansible AWX and then choose ELK_stack yml file. After entering the inputs for this project ELK Stack and Curator will be installed.

### Redis-Server and Sentinel Installation

Redis Sentinel will be lifeguard for the successfully communication to prevent disaster issues between Redis-Server. Enter the inputs in AWX to install both of them (redis-server and sentinel)

### RabbitMQ Installation

You need to define your rabbitmq.sh script file to install Rabbitmq in you linux environment. The yml file for rabbit will call this .sh file to reduce the number of lines in legibility.

### Uninstall a mw app in AWX

To uninstall any application in your linux environment without connection. Enter the name of app and then the applications will be deleted.
