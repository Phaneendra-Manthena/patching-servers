pipeline {
  agent {
        label 'workstation'
    }

    stages {
        
        stage('Run Ansible Playbook') {
  steps {
    ansible-playbook test.yml
                   
    }
  }
 }
}
