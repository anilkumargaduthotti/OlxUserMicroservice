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
                echo 'Compiling'
            }
        }
        stage('run') {
            steps {
                echo 'running'
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
