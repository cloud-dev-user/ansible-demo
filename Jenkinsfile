pipeline {
  agent any
  stages {
    stage('demo') {
      steps {
        sh 'echo " Hello WOrld "'
      }
    }
     stage('demo') {
      steps {
        sh 'ip a &&  ansible-playbook demo.yaml'
      }
    }
  }
}
