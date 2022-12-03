pipeline {
    agent any
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