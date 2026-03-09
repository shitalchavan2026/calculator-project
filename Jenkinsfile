pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/shitalchavan2026/calculator-project.git'
            }
        }

        stage('Build') {
            steps {
                echo "Build stage running"
            }
        }

        stage('Run') {
            steps {
                echo "Application running"
            }
        }
    }
}
