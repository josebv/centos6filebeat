# filebeat role for centos6

## Steps to make it work

1. git clone https://github.com/josebv/centos6filebeat
2. Edit the `inventory` file with the ips and private key
3. ansible-playbook -i inventory main.yml 
