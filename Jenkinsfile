pipeline {
    agent any 
    stages {
        stage('checkout') { 
            steps {
            git 'https://github.com/jawajiwar/vetinary-care-solutions.git' 
            }
        }
        stage('Build') { 
            steps {
                sh 'mvn clean package' 
            }
        }
        }
        }
