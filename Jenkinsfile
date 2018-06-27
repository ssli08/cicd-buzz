pipeline {
    agent {
        docker {
            image '7db65d51c42b94c6ecaf28bc4ffa47a51ede7c71:latest'
            args '-p 5000:5000'
        }
    }
   stages {
        stage("test env") {
            steps {
		sh 'top'
                sh 'curl -I http://localhost:5000'
            }
        }
	}
}
