pipeline {
    agent { any { image 'maven:3.6-openjdk-8' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
