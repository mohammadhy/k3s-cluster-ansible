# k3s-cluster-ansible
Install All Requirment For Devops Training 
This Package contains Redis - Mysql - Gitea - Jenkins - Registry - Elasticsearch - Kibana
as easy as possible create cluster kubernetes with K3s and running some tools for Devops.
## requirment
Before go through be sure ansible installed on youre mashine and check connection.
Just edit inventory.yaml and edit Machine IP slave, master
## Run
apt install sshpass
vim /etc/ansible/ansible.cfg


  [defaults]

  
  host_key_checking=false

  
ansible-playbook -i inventory.yaml tasks/main.yaml
