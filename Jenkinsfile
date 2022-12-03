pipeline {
    agent any
    tools {
        nodejs 'NodeJS@19.2.0'
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