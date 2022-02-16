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
        sh """curl -u uttam-dubey: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 https://api.github.com/user
          
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
