pipeline {
    agent any
    tools { nodejs "NodeJS@18.8.0" }
    stages {
        stage('Example') {
            steps {
                sh '''
                    npm ci
                    npm run build
                '''
            }
        }
    }
}