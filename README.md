# CloudFormation-Template
  Automate the deployment of a Jenkins Server within a Custom Network in AWS using Cloud Formation

 # CBAJenkisTemplate.yml 
  Deploy a cloud formation template to AWS from Jenkins 

# AnsibleTemplate.yaml

Deploy 2 EC2 instances with Ansible installed on Main server and also create Ansible.cfg and Inventory file 


# Commands to Run 

aws cloudformation validate-template --template-body file://[name of yaml file as stored] --region eu-west-2
-   
- This validates the script and checks for any syntax error

aws cloudformation deploy --template-file [name of yaml file on your local host] --stack-name ec2 --region eu-west-2
- 
- Deploys the cloud formation stack named ec2 using the template file and sets the region to eu-west-2

aws cloudformation delete-stack --stack-name ec2 --region eu-west-2
- 
- Deletes the stack 
