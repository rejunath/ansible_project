# ansible_project
1. ec2-instance needs to be created: 

    *ansible-playbook create_remote_instance.yml*
    
2. For deploying in remote machine:

   *ansible-playbook -i hosts app_deploy_remote_server.yml*
   
  
 **Note:**\
     * values in reference.yml need to be updated.\
     * Aws secret ID and Access key need to be included in bashrc\
     * ip-address need to be updated in hosts
     
     
    
  
    
    
