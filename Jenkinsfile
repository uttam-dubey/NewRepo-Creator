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
        sh """curl -i -u uttam-dubey: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 https://api.github.com/users/octocat
          
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
