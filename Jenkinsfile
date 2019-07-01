pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                bat(/"%MVN_HOME%\bin\mvn" --version/)
            }
        }
    }
}
