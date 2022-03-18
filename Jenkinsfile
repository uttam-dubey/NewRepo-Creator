pipeline {
  agent any
  stages {
    stage('Worldly') {
      steps {
        sh """pwd
              ls /bitnami/jenkins/home/workspace/Mypipeline_main
              chmod +x ./script.sh
              ./script.sh
          """
      }
    }
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
