# Web Infrastructure Design

Upload screenshots of various web infrastructure designs. Album of all screenshots are here: https://imgur.com/a/fQcaVUd

## Files in This Repository
| File Name | Description |
| --- | --- |
|[0-simple_web_stack](https://github.com/Alouie412/holberton-system_engineering-devops/blob/master/0x09-web_infrastructure_design/0-simple_web_stack) | Basic web infrastructure design, using 1 server (physical or digital), 1 web server, 1 application server, 1 code base, 1 database, 1 domain, and 1 browser. Note the possibility of SPOF |
|[1-distributed_web_infrastructure](https://github.com/Alouie412/holberton-system_engineering-devops/blob/master/0x09-web_infrastructure_design/1-distributed_web_infrastructure) | Web infrastructure design utilizing a load balancer. We are basically duplicating the simple web stack from the previous task and connecting them both to a load balancer. This offers far more advantages compared to a simple web stack, but still has its disadvantages. Still note the SPOF possibility here |
[2-secured_and_monitored_web_infrastructure](https://github.com/Alouie412/holberton-system_engineering-devops/blob/master/0x09-web_infrastructure_design/2-secured_and_monitored_web_infrastructure) | Web infrastructure design utilizing a load balancer, now made secure using monitoring clients, firewalls, and an SSL certificate. Also utilizing HTTPS over HTTP for encryption, this otherwise basic design allows for secure connection as well as minimizing chances of downtime |
[simple_web_stack.png](https://github.com/Alouie412/holberton-system_engineering-devops/blob/master/0x09-web_infrastructure_design/simple_web_stack.png) | Image version of 0-simple_web_stack, should the imgur link fails |
[distributed_web_infrastructure](https://github.com/Alouie412/holberton-system_engineering-devops/blob/master/0x09-web_infrastructure_design/distributed_web_infrastructure.png) | Image version of 1-distributed_web_infrastructure, should the imgur link fails |
[secured_and_monitored_web_infrastructure](https://github.com/Alouie412/holberton-system_engineering-devops/blob/master/0x09-web_infrastructure_design/secured_and_monitored_web_infrastructure.png) | Image version of 2-secured_and_monitored_web_infrastructure, should the imgur link fail |
