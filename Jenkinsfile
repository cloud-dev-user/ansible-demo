pipeline {
  agent any
  stages {
    stage('demo') {
      steps {
        sh 'echo " Hello WOrld "'
      }
    }
     stage('ansible playbook deployment') {
      steps {
        sh 'ip a &&  ansible-playbook demo.yaml'
      }
    }
  }
}
