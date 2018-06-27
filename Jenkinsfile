pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
		sh "echo ${env.BUILD_ID}"
		sh 'ls'
		sh "echo $Image.tag}"
            }
        }
    }
}
