pipeline {
    agent { dockerfile true } 
    stages {
	stage('validate') {
		steps {
			whoami
			}
		}
	stage('Test'){
		steps {
			docker ps
			}
		}
            }
}
