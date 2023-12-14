# Use Terraform to provision infrastructure

# Description:

Nowadays, infrastructure automation is critical. We tend to put the most emphasis on software development processes, but infrastructure deployment strategy is just as important. Infrastructure automation not only aids disaster recovery, but it also facilitates testing and development.

Your organization is adopting the DevOps methodology and in order to automate provisioning of infrastructure there's a need to setup a centralised server for Jenkins.

Terraform is a tool that allows you to provision various infrastructure components. Ansible is a platform for managing configurations and deploying applications. It means you'll use Terraform to build a virtual machine, for example, and then use Ansible to instal the necessary applications on that machine.

Considering the Organizational requirement you are asked to automate the infrastructure using Terraform first and install other required automation tools in it.


# tf-get-jenkins-on-cloud
This terraform code will install Jenkins in cloud and get you IP and URL details on terminal. 
1. Please modify your provider section with your lab specific detais
2. Run following command
   ```
   terraform init
   ```
   ```
   terraform plan
   ```
   ```
   terraform apply
    ```

4. Get initial admin password, use this command
   ```
   sudo cat /var/lib/jenkins/secrets/initialAdminPassword
   ```
6. Install Following plugins after you login to jenkins
- docker build step
- docker pipeline
- delivery pipeline
- docker common plugins 
