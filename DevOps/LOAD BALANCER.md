# LOAD BALANCER

##### Used to handle load on server by creating multiple servers and switching between the servers depending on the load.



1. create 3 instances with same key and same security group with different subnet in same region and allow port http 80.
2. create target group with these three instances.
3. create load balancer.
4. yum install httpd
5. cd /var/www/html/
6. cat > index.html => server 1
7. cd
8. yum install curl
9. curl http:/localhost (run these commands on all the instances terminals os of these instances can be different)
10. open dns of load balancer in browser refresh to see which server is currently working. 
