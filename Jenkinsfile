pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World!!!!'
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
