pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello Build'
            }
        }
        stage('Test') {
            steps {
                echo 'Hello Test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Hello Deploy'
            }
        }
    }

    post {
        always {
            echo "i will always say hello again !"
        }
        success {
            echo "wihiiiyy, Success"
        }
        failure {
                    echo "Oh Nooo, Fake"
        }
        cleanup {
                    echo "dont care success or error"
        }
    }
}
