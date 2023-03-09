/* Requires the Docker Pipeline plugin */
pipeline {
    agent { 
        docker { 
            image 'python:3.10.7-alpine'
                args '-v "C:/Users/Tony Lundén/.jenkins/workspace/Jenkinstest_main/":/c/DevOps/'
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
