pipeline{
  agent any  
  stages{  
      stage("Run an ansible playbook"){
        steps{
          ansiblePlaybook credentialsId: 'ssh', inventory: 'hosts', playbook: 'nginx_install.yaml'
        }
      }
  }
}
