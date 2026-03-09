pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'main', url: 'https://github.com/shitalchavan2026/calculator-project.git'
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
