pipeline {
    agent any
    environment {
        PROJECT_NAME = "My First Declatative Pipeline"
        DEVELOPER_NAME = "abakulin"
    }
    stages {
        stage('first-stage') {
            steps {
                echo "Hello from first stage!"
                echo "Stage started"
                echo "Do something... ${PROJECT_NAME}, developer is ${DEVELOPER_NAME}"
                echo "Stage finished"
            }
        }
        stage('second-stage') {
            steps {
                echo "Good bye, bad boy, ${DEVELOPER_NAME}"
            }
        }
    }
}
