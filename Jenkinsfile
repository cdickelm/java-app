pipeline {
  agent any
  stages {
    stage('Nonsense') {
      steps {
        echo 'Hello, world!'
      }
    }
    stage('maven build') {
      steps {
        sh 'mvn clean package -DskipTests'
      }
    }
  }
}