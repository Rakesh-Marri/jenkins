pipeline {
    agent any
    stages {
        stage('build step')
         {
            steps {
               echo "this is for testing"
          }
        }
        stage('deploy test') {
            steps {
              sh 'cat /etc/os-release'
       }
    }
  }
}
