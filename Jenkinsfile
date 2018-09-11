pipeline {
    agent linux_01

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                java -version
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
