pipeline {
    agent any
    environment {
        python_path="C:\\Python\\python.exe"
    }
    stages {
        stage('Build') {
            steps {
                bat "${python_path} code.py" 
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
