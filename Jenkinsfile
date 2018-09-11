pipeline {
    agent { label 'linux_01' }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                script 'sh java -version'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
