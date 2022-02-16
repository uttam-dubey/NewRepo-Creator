pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        sh """curl \
              -H "Accept: application/vnd.github.v3+json" \
              https://api.github.com/repos/uttam-dubey/test1
          
          """
      }
    }
    stage('World') {
      steps {
        sh """curl -H "Authorization: token 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" --data '{"name":"Mynewrepo"}' https://api.github.com/user/repos
          
          """
      }
    }
  }
}
