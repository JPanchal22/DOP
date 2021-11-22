pipeline {
    agent any

    stages {
        stage('Build & Test') {
            steps {
                mvn clean package
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
