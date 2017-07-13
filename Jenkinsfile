pipeline {
    agent { sh 'mvn -v' }
    stages {
        stage('build') {
            steps {
                sh 'mvn clean'
            }
        }
    }
}

