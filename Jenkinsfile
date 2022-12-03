pipeline {
    agent {
        docker { image 'node:16.13.1-alpine' }
    }
    stages {
        stage('Example') {
            steps {
                sh '''
                    npm install
                    npm build
                '''
            }
        }
    }
}