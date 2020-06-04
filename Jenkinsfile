pipeline {
  agent any
  stages {
    stage('Dev') {
      steps {
        sh 'echo "hello world this is from dev"'
      }
    }

    stage('Test') {
      steps {
        sh 'echo "hello this is from test"'
      }
    }

    stage('Deploy') {
      steps {
        sh 'echo "deploy on production"'
      }
    }

  }
}