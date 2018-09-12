#!groovy

pipeline {
    agent { label 'linux_01' }
     
    stages {
        stage('Build') {
            steps {
                echo 'Contruindo..'
                script {'sh java -version'}
                 sh '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
                ''' 
            }
        }
        stage('Test') {
            steps {
                echo 'testando..'
            }
        }
        stage('Package') {
            steps {
                echo 'Empacotando....'
            }
        }
        
        stage('Nexus') {
            steps {
                echo 'Versionando e guardando....'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Implantando no Ambiente @ParamAmbiente DEV CERT HOM....'
            }
        }
    }
}
