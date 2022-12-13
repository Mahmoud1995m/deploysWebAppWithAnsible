# simpleWebApp

This code to automate install git , httpd in all hosts that exist in the inventory in controller server , then copy the html simple web application to target destination 

to run the playbook as shown below.

ansible-playbook -i /home/ansible/inventory /home/ansible/web.yml

the inventory as shown below.

[ansible@control1 ~]$ cat /home/ansible/inventory
[web]
node1
node2
