pipeline {
    agent {
        docker {
            image 'maven:3.6.3'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn --version'
                echo "mvn --version"
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

