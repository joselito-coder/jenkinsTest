

/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'python:3.14.2-alpine3.23' } }
    stages {
        stage('build') {
            steps {
                sh 'python hello.py'
		sh 'ls'
		sh "echo watashi wa hangy famboi ninja"
            }

        }
    }
}


