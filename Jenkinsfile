pipeline{
  agent any  
  stages{  
      stage("Run an ansible playbook"){
        steps{
          ansiblePlaybook credentialsId: 'sshkey', inventory: 'hosts', playbook: 'nginx_install.yaml'
        }
      }
  }
}
