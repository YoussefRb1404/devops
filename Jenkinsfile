pipeline {
    agent any

    stages {
        stage('Hello') {          
            steps {
                echo 'Hello world!'
            }
        }

        stage('Checkout') {    
            steps {
                git url: 'https://github.com/YoussefRb1404/devops.git', branch: 'master'
            }
        }

        stage('Maven') {         
            steps {
                sh 'mvn -version'
            }
        }
    }
}
