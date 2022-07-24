pipeline{
  agent any  
  stages{  
      stage("Run an ansible playbook"){
        steps{
          sh 'ansible all -m ping -v'
          sh 'ansible-playbook -i hosts nginx_install.yaml'
        }
      }
   }
}
