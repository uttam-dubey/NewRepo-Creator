pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        sh """
              curl https://api.github.com/users/uttam-dubey
          """
      }
    }
    stage('New') {
      steps {
        sh """
            pwd
          """
      }
    }
    
  }
}
