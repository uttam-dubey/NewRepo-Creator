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
        sh """curl \
                -X POST \
                -H "Accept: application/vnd.github.v3+json" \
                https://api.github.com/repos/uttam-dubey/test1/generate \
                -d '{"uttam-dubey":"latestone"}'
          
          """
      }
    }
  }
}
