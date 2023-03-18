/* Requires the Docker Pipeline plugin */
/*Jenkins Docker Pipeline plugin on the Windows host can't execute Linux Docker images due to a bug. Therefore updating the pipeline*/
/*
pipeline {
    agent { docker { image 'python:3.10.7-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                echo "on enable-jenkins branch"
            }
        }
    }
}
*/
pipeline {
    agent none
    stages {
        stage('build') {
            steps {
                echo "Hello World on enable-jenkins branch"
            }
        }
    }
}
