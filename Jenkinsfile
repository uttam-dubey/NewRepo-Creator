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
