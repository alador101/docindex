pipeline {
    stages {
        stage('Checkout eliab') {
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'test1', url: 'https://github.com/alador101/docindex.git']]])
            }
        }
    }
}
