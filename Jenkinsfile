stages {Add commentMore actions
        stage('Clean') {
            steps {
               
                sh cd C:/Users/343629/AnypointStudio/studio-workspace/emp-app 'mvn clean'
            }
        }

         stage('Build') {
            steps {
               
                sh 'mvn install'
            }
        }
         stage('Test') {
            steps {
               
                sh 'mvn test'
            }
        }
         stage('Deploy') {
            steps {
               
                sh 'mvn deploy'
            }
        }
    }
