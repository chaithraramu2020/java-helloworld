pipeline {
    agent {label 'slave3-java'}
    stages {
        stage('build') {
            steps {
                sh 'mvn compile'
            }
        }
         stage('test') {
            steps {
                sh 'mvn test'
            }
        }
         stage('deploy') {
            steps {
                echo 'deploy success'
            }
        }
    }
}
