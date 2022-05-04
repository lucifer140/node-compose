pipeline {
    agent any

    stages {
        stage('composing') {
            steps {
                echo 'Hello World'
                sh '''
                docker-compose up -d
                docker ps
                '''
                
            }
        }
    }
}
