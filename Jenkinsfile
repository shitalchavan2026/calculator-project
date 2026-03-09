pipeline {
    agent any

    stages {

        stage('Checkout Code') {
            steps {
                git git 'https://github.com/shitalchavan2026/calculator-project.git'
            }
        }

        stage('Build') {
            steps {
                bat 'g++ main.cpp -o main.exe'
            }
        }

        stage('Run') {
            steps {
                bat 'main.exe'
            }
        }
    }
}
