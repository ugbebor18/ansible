pipeline{
  agent any  
  stages{
    
      stage("Git Checkout"){
        steps{
          sh 'git clone https://github.com/obiomaokorowu/ansible_Demo.git'
        }
      }
      
      stage("Run an ansible playbook"){
        steps{
          sh 'ansible-playook nginx_install.yaml '
        }
      }
   }
}