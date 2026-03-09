pipeline {
    agent any

    stages {

        stage('Checkout Code') {
            steps {
                git 'https://github.com/your-username/your-repo.git'
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
