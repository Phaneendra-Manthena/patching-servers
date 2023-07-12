pipeline {
  agent {
        label 'workstation'
    }

    stages {
        
        stage('Run Ansible Playbook') {
  steps {
    sh "ansible-playbook test.yml"
                   
    }
  }
 }
}
