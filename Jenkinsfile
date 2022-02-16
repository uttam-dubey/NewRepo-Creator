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
        sh """curl -H "Authorization: token ACCESS_TOKEN" --data '{"name":"NEW_REPO_NAME"}' https://api.github.com/user/repos
          
          """
      }
    }
  }
}
