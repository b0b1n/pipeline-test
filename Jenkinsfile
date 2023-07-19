pipeline {
  agent any

  stages {
    stage("build") {
      steps {
        echo 'Building the application...'
      }
    }
    stage("test") {
      steps {
        echo 'Built the application\n'
        echo 'Testing the application...'        
      }
    }
    stage("deploy") {
      steps {
        echo 'Tested the application\n'
        echo 'Deploying the application...'        
      }
    }
  }
}
  
