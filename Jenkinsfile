pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
		sh "curl http://${hostname}:5000"
            }
        }
    }
}
