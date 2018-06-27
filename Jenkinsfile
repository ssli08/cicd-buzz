pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
		sh 'top'
		sh "curl http://localhost:5000"
            }
        }
    }
}
