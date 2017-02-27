pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                checkout scm
                withMaven(
                    maven: 'Maven 3.x') {

                    // Run the maven build
                    sh "mvn clean install"
                }
            }
        }
        stage('Tests'){
            steps {
                withMaven(
                    maven: 'Maven 3.x') {

                    // Run the maven test
                    sh 'mvn test'
                }

            }
        }
    }
}