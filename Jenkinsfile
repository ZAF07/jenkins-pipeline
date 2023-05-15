pipeline {
    agent any

    environment {
        NEW_VERSION = "1.0.0"
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building rick after 888 update ..'
                echo "bUILDING NEW VERSION: ${NEW_VERSION}"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing rick..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying rick....'
            }
        }
    }
}
