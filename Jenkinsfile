pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'sudo -n docker run --rm -i -p 3000:3000/tcp my-app-one:latest'
      }
    }

  }
}