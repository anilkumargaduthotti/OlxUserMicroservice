pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/mohammadazeez963/javaProject.git'
            }
        }
        stage('Compile') {
            steps {
                bat 'mvn clean compile'
            }
        }
        stage('run') {
            steps {
                bat 'mvn package'
            }
        }
         stage('test report using jacoco') {
            steps {
                echo 'jacoco'
            }
        }
        stage('Building Docker Image') {
            steps {
                echo 'Building Docker Image'
            }
        }
    }
}
