pipeline {
  agent {
    docker {
      image 'maven:alpine'
      args 'library \'SharedLibs\''
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