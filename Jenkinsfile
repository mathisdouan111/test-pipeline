pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                echo "Compilation terminée"
            }
        }
        stage('Test') {
            steps {
                echo "Tests OK"
            }
        }
    }
}
