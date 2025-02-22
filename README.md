# 4640-w7-lab-start-w25

Starter files for the intro to Ansible lab.

See D2L for lab instructions

Generate new keys: ssh-keygen -t rsa -b 2048 -f ~/.ssh/aws -N ""
    -This command generates the aws public and private keys in the directory ~/.ssh
Run Terraform config and apply:
    - terraform init
    - terraform apply -auto-approve
Running playbook.yml file: ansible-playbook -i inventory/host.yml playbook.yml
    -This command runs the playbook.yml file while also looking in the inventory directory and
    using the host.yml file in there to use the ec2 instances' IP addresses.
Visited the url specified in ec2 instance, and have the screenshot shown in the github repo
