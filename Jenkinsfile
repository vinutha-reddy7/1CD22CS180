pipeline {
    agent any
    tools {
        maven 'MAVEN_HOME' // Make sure this matches Maven name in Jenkins
    }
    stages {
        stage('Build') {
            steps {
                bat 'mvn clean install'
            }
        }
    }
}
