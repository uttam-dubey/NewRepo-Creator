pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        sh """curl --header "Authorization: token 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" \
              https://api.github.com/uttam-dubey/test1

          """
      }
    }
    stage('World') {
      steps {
        sh """curl -H "Authorization: token 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" --data '{"name":"Mynewrepo"}' https://api.github.com/uttam-dubey/repos
          
          """
      }
    }
  }
}
