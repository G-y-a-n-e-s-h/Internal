pipeline {
    agent any

    stages {
       stage('Checkout') {
            steps {
                  checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'd91f3581-a7cd-4ff7-98e5-670d06493ad5', url: 'https://github.com/G-y-a-n-e-s-h/Internal.git']])
            }
        }
    }
}
