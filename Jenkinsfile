Pipeline{
    stages{
        stage("Github repo")
            sh """
            curl \
              -H "Accept: application/vnd.github.v3+json" \
              https://api.github.com/repos/uttam-dubey/test1
            """
          }
}
