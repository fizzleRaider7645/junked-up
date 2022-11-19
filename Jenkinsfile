pipeline {
    agent any
    tools { nodejs "NodeJS@18.8.0" }
    stages {
        stage('Example') {
            steps {
                sh '''
                    yarn install
                    yarn run build
                '''
            }
        }
    }
}