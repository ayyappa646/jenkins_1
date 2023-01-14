pipeline {
  agent { labal 'test'
    }
  
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
    stage ('this is third stage from the jenkins'){
      steps ("thirs stage"){
        echo "thirs stage from the git and github"
        }
       }
      stage ('fourth') {
        steps (fourth) {
          echo ("fourth")
          }
      }
  }
}
