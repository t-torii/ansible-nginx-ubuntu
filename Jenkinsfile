pipeline {
  agent any
  stages {
    stage('ansible-test') {
      steps {
        ansiblePlaybook(playbook: 'site.yml', become: true, becomeUser: 'root', credentialsId: '9f38c819-ef9c-476d-9634-df1ba67677f0')
      }
    }
  }
}