pipeline {
    agent any

    stages {
        stage('Clean') {
            steps {
                echo 'Clean Project'
            }
        }
        
         stage('Build') {
            steps {
                echo 'Build Project'
            }
        }
         stage('Test') {
            steps {
                echo 'Test Project'
            }
        }
         stage('Deploy') {
            steps {
                sh 'mvn deploy'
            }
        }
    }
}
