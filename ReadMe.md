Explain stuff here

sudo apt update && sudo apt upgrade
sudo apt install ansible
sudo apt upgrade ansible

ansible -m ping node1 -i inventory
ansible -m ping node2 -i inventory
ansible -m ping controlnode -i inventory

ansible-playbook webservers.yml -i inventory
ansible-playbook InstallJava.yml -i inventory
ansible-playbook InstallJenkins.yml -i inventory

sudo cat /var/lib/jenkins/secrets/initialAdminPassword
