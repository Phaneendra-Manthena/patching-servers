pipeline {
  agent {
        label 'slave'
    }

    stages {
        
        stage('Run Ansible Playbook') {
  steps {
    ansiblePlaybook becomeUser: 'ansible',
                   colorized: true,
                   credentialsId: 'ansible-privatekey',
                   installation: 'Ansible',
                   inventory: './hosts',
                   playbook: './patch.yml'
  }
}
    }
}
