pipeline {
  agent any 
  
  stages {
    stage ('this is first stage'){
      steps {
        echo "this is the first of the pipe line"
        }
     }
  stage ('thisnis second satge from the'){
    steps {
      echo "this is second stage from the jenkins"
      }
     }
  }
}
