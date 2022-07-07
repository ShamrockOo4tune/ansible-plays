#nginx_on_centos  
================  

This role installs and configures nginx web server on Centos host  

##Requirements  
------------  

**ansible** user should be configured on remote host.  
**ansible** users password is encoded with **ansible-vault** and stored in **../../group_vars/become_password** file  

##Example Playbook  
----------------  

There is an example playbook **../../web-tls-playbook.yaml**  
The file is executable, assuming run on linux with **/bin/ansible-playbook** available  

License  
-------  

BSD  

Author Information  
------------------  

Shamil Gumerov 
shamusg12345@gmail.com
