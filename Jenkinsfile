pipeline {
  agent any
  stages {
      stage("Build") {
          steps {
            sh "df -h" 
          }
      }
      stage("Test") {
          steps {
              echo "Test"
          }
      }
      stage("Deploy") {
          steps {
              echo "Deploy"
          }
      }
  }
}
