pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                def mvnHome = tool 'M3'
                bat "\"${mvnHome}\"\\bin\\mvn --version"
            }
        }
    }
}
