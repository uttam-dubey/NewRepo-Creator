pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        sh """curl \
              -H "Accept: application/vnd.github.v3+json" \
              https://api.github.com/repos/octocat/hello-world
          
          """
      }
    }
  }
}
