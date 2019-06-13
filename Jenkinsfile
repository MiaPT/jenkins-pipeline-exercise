pipeline {
    agent any

    stages {
        stage('Preparation') {
            steps {
                echo 'Preparation..'
            }
        }
        stage('Build') {
            steps {
                echo 'Build'
                sh './gradlew clean test jar'
            }
        }
        stage('Result') {
            steps {
                echo 'Result'
            }
        }
    }
}
