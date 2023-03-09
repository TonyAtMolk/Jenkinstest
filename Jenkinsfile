/* Requires the Docker Pipeline plugin */
pipeline {
    agent { 
        docker { 
            image 'python:3.10.7-alpine'
            label 'my-jenkinstest'
            ars '-v $(pwd):/opt \' '-w /opt \'
               } 
          }
    stages {
        stage('build') {
            steps {
                echo 'Hello Jenkins!'
            }
        }
    }
}
