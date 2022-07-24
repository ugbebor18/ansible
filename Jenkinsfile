pipeline{
  agent any  
  stages{  
      stage("Run an ansible playbook"){
        steps{
          sh 'ansible-playook nginx_install.yaml '
        }
      }
   }
}
