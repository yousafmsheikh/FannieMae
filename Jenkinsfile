pipeline {
  agent {
    docker {
      image 'maven:alpine'
    }
    
  }
  stages {
    stage('MyFirstStage') {
      steps {
        sh '''mvn -v

stage(\'Shared Lib\') {
         steps {
             helloWorld("Jenkins")
         }
      }'''
      }
    }
  }
}