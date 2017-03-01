pipeline {
    agent any
    tools {
        maven 'Maven 3.x'
    }
    stages {
        stage('Build') {
            steps {
                sh "mvn clean install"
            }
        }
        stage('Tests'){
            steps {
                sh 'mvn test'
            }
        }
    }
}