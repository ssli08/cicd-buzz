pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
		sh "echo ${env.BUILD_ID}"
		//sh "echo ${docker.Image.tag('ssli-test')}"
            }
        }
    }
}
