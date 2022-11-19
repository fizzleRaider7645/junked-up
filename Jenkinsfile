pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                sh 'npm ci && npm run build'
            }
        }
    }
}