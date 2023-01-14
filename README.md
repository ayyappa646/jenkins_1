pipeline {
  agent any 
  
  stages {
    stage ('this is first stage'){
      steps {
        echo "this is the first of the pipe line"
        }
     }
  }
}
