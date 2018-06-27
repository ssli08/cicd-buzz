pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
		sh "echo ${env.BUILD_ID}"
            }
        }
    }
}
