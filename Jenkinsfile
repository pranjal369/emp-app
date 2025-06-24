pipeline {
    agent any

    stages {
        stage('Clean') {
            steps {
               mvn clean
            }
        }
        
         stage('Build') {
            steps {
                sh 'mvn build'
            }
        }
         stage('Test') {
            steps {
                 sh 'mvn test'
            }
        }
         stage('Deploy') {
            steps {
                 sh 'deploy'
            }
        }
    }
}
