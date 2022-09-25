pipeline{
  agent any  
  stages{  
      stage("Run ansible playbook"){
        steps{
          ansiblePlaybook credentialsId: 'sshkey', inventory: 'hosts', playbook: 'nginx_install.yaml'
        }
      }
  }
}
