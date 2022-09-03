pipeline {
  agent any
  environment {
    PROJECT_NAME = "Jenkins Come On Project"
    DEVELOPER = "alex-fossa"
  }
  stages {
    stage('first-stage') {
      echo "Build started"
      echo "Hello, ${DEVELOPER}"
      echo "Your project had been built successfully, project name is ${PROJECT_NAME}"
    }
    stage('last-stage') {
      echo "Good bye, mister ${DEVELOPER}"
    }
  }
}
