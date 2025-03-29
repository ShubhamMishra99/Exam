pipeline {
    agent any
    tools {
        maven 'maven'  // Use the exact name you set in Global Tool Configuration
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
    }
}
