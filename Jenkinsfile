pipeline {
    agent {
        docker { image 'node:16-alpine' }
    }
    stages {
        stage('Example') {
            steps {
                sh '''
                    yarn install
                    yarn build
                '''
            }
        }
    }
}