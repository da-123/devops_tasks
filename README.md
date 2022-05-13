# devops_tasks
paths to look at 
to find the compose file 
1, cd /home/ubuntu/drupal/docker-compose.yml
Drupal:
web address:http://drupal.3.110.209.93.nip.io/
   this can not able to to get ssl cerfifacte since it nip.io , since have no control to create/modify dns records on nip.io but i have configured to be redirected to to https on this path , cd /home/ubuntu/durpal/nginx-conf/nginx.conf.bkp2  nginx is responding cerficate error issue since it's nip.io so i drop this conf and used /home/ubuntu/durpal/nginx-conf/nginx.conf
i did use c advisor for montoring docker container with promethus 
ip address :cadvisor:http://3.110.209.93:8080/ and promethus :http://3.110.209.93:9090
you can find conf for prometehus on vi /etc/prometheus/prometheus.yml i have inculde all the container's on that as well 
i have allowed the server to be accessed over ssh will shared over email.both username and password: for secuirty purposes 
