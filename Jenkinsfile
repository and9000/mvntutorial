pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                withMaven(
                    maven: 'Maven 3.x') {

                    // Run the maven build
                    sh "mvn clean install"
                }
            }
        }
        stage('Test'){
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