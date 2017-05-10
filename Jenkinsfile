pipeline {
  agent any
  stages {
    stage('shell script') {
      steps {
        parallel(
          "shell script": {
            sh 'echo "hi"'
            
          },
          "": {
            sh 'sleep 30'
            
          }
        )
      }
    }
  }
}