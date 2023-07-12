pipeline {
  agent {
        label 'workstation'
    }

    stages {
        
        stage('Run Ansible Playbook') {
  steps {
    ansiblePlaybook becomeUser: 'mpvarma9997',
                   colorized: true,
                   credentialsId: 'ansiblesshkey',
                   installation: 'ansible',
                   inventory: './hosts',
                   playbook: './test.yml'
    }
  }
 }
}
