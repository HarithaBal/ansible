pipeline{
   agent any
   stages{
   	stage("Execute Ansible"){
   	 steps{
        ansiblePlaybook credentialsId: 'Ansible', disableHostKeyChecking: true, installation: 'Ansible', inventory: 'dev.inv', playbook: 'apache.yml'	 
   	 }
   	}
  }
}
