# Debug Assignment CDO


## Terraform 

To provision EC2 instance using Terraform navigate to Terraform directory `cd Terraform`

- Initalise terraform `terraform init`
- Run `terraform apply`


## Run Ansible Playbooks

To configure EC2 instance you will first need to

 1. Navigate to ansible folder `cd ansible`
 2. Run `ansible-playbook playbooks/docker-install.yml` 
    - This will install Docker and Docker compose
 3. Run `ansible-playbook playbooks/docker-run.yml`


 ## Endpoints 

 Examples endpoints which should be reachable:

- <ec2-instance-ipv4-ip-address>:3000/tour-de-france/cyclists
- <ec2-instance-ipv4-ip-address>:3000/tour-de-france/teams





