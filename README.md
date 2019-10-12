# deploy_webserver
The deploy_playbook installs httpd server on hosts under ansible_hosts. 
It also copies index.html to target machine which displays "Hello World" when opened on browser
After copying the file, it starts apache webserver

#undeploy_webserver
The undeploy_playbook removes the html file. 

