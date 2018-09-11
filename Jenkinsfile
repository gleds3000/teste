pipeline {
    agent linux_01

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                javac --version
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
