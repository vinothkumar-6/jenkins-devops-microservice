pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Build"
                echo "Test"
                echo "Integration Test"
            }
        }
        stage('test') {
            steps {
                echo "Build"
                echo "Test"
                echo "Integration Test"
            }
        }
        stage('Itest') {
            steps {
                echo "Build"
                echo "Test"
                echo "Integration Test"
            }
        }
    }
    post {
        always {
            echo 'I am Super. messi!'
        }
        success {
            echo 'I am fast. Ronaldo!'
        }
        failure {
            echo 'Bitch please. Jai Balaiya!'
        }
    }
}
