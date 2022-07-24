pipeline{
  agent any  
  stages{  
      stage("Run an ansible playbook"){
        steps{
          sh 'ansible-playook -i hosts nginx_install.yaml '
        }
      }
   }
}
