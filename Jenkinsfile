pipeline {
    agent any
    stages {
        stage('Compile') {
            steps { 
      		sh 'mvn clean'
                sh 'mvn compile'
            }
        }
        stage('Test') {
            steps { 
                sh 'mvn test'
            }
        }
        stage('Package') {
            steps { 
                sh 'mvn package'
            }
        }
    }
}
