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
    }
}
