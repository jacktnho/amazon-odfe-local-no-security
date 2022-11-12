# amazon-odfe-local-no-security
Set up local ElasticSearch node and Kibana based on amazon open distro (v7.10.4)
Security features of ElasticSearch and Kibana are switched off intentionally for testing under local network. 
 
To run the node and kibana server
```
docker-compose up
```
Then, a ES node is launched at localhost:9200 while a Kibana server is launched and serving at localhost:5601
