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
        stage('shell scripting') {
            steps {
              sh 'curl -k http://localhost:8080'
      }
     }
  }
}
