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
        sh """curl -i -u your_username:$token https://api.github.com/users/uttam-dubey
          
          """
      }
    }
    stage('World') {
      steps {
        sh """curl -H "Authorization: token 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" --data '{"name":"Mynewrepo"}' https://api.github.com/users/uttam-dubey
          
          """
      }
    }
  }
}
