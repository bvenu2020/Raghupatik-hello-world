pipeline{
    agent {label 'java1'}

    stages {
        stage('Checkout') {
            steps {
                echo 'Checkout' 
                checkout scm
            }
        }

        stage('Build') {
            steps {
                // script
                sh 'mvn clean install'           
            }
        }
    }
}
