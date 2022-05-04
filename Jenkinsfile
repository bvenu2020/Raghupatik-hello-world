pipeline{
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Checkout' 
                // script
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
