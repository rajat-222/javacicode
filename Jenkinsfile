pipeline {

    agent any

    stages {
        stage('GIT Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/rajat-222/javacicode.git'
            }
        }
        stage('UNIT TESTING'){
            steps{
                sh 'mvn test'
            }
        }
    }
}