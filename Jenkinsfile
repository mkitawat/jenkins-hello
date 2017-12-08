pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat 'mkmaven; mvn --version'
            }
        }
    }
}