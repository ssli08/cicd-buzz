pipeline {
    agent { dockerfile true } 
    stages {
	stage('Test'){
	try {
           			 // Start database container here
		            	 // sh 'docker run -d --name db -p 8091-8093:8091-8093 -p 11210:11210 arungupta/oreilly-couchbase:latest'

			         // Run application using Docker image
				//            sh "DB=`docker inspect --format='{{range .NetworkSettings.Networks}}{{.IPAddress}}{{end}}' db`"
			        //    sh "docker run -d -p 9001:9001 daocloud.io/suqun/docker-jenkins-pipeline:${env.BUILD_NUMBER}"

            // Run tests using Maven
            //dir ('webapp') {
            //  sh 'mvn exec:java -DskipTests'
            //}
		sh 'docker ps'
        } catch (error) {
        } finally {
            // Stop and remove database container here
            //sh 'docker-compose stop db'
            //sh 'docker-compose rm db'
        }
			}
		}
            }
