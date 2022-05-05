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
                echo 'Build'
                sh 'mvn clean install'           
            }
        }
    }
}
