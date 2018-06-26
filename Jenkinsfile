pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
		sh 'docker ps -a'
                sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}
