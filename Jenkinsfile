pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        parallel(
          "build": {
            sh 'echo "test"'
            
          },
          "upload": {
            echo 'testing steps'
            
          }
        )
      }
    }
  }
}