pipeline {
    agent any 
    stages {
        stage('Checkout main') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'test1', url: 'https://github.com/alador101/docindex.git']]])
            }
        }
    }
}
