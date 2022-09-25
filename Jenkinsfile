pipeline{
  agent any  
  stages{  
      stage("Run an ansible playbook"){
        steps{
          ansiblePlaybook credentialsId: 'sshkey', installation: 'ansible2', inventory: 'hosts', playbook: 'nginx_install.yaml'
        }
      }
  }
}
