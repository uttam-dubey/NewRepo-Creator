pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        sh """curl \
                -X POST \
                -u uttam-dubey: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 \
                -H "Accept: application/vnd.github.v3+json" \
                https://api.github.com/orgs/uttam-dubey/repos \
                -d '{"name":"Newrepofor-test"}
          
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
