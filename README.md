# Prerequisites
#
- JDK 11 
- Maven 3 
- MySQL 8
- Vagrant v2.3.7

# AWS Services
- ACM (AWS Certificate Manager)
- ELB (Elastic LoadBalancer)
- EC2 (Elastic Compute Cloud) => For Tomcat Web Server, Backend: MySQL, Memcached, RabbitMQ server
- S3 (Simple Storage Service) => For Storing Artifacts
- Amazon Route 53 => For DNS Private Zone
- Auto Scaling => For auto scaling Tomcat Web Server base on CPU Usage(Reach more 50%)

  
# Tech stacks
![image](https://github.com/bxlldev/vprofile-project-public-aws/assets/127035655/a6c15868-df9c-4eec-8ef5-456beedbce76)
- DNS Provider => GoDaddy
- Load Balancer => Nginx => ELB
- Java web application server => Apache Tomcat => EC2
- External Storage => NFS
- Messaging Broker => RabbitMQ => EC2
- Caching Server => Memcached => EC2
- Database Server => MySQL (MariaDB service) => EC2
