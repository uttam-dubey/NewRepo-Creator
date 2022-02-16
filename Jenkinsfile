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
