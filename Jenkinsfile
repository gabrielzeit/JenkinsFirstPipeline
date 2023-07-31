/* Requires the Docker Pipeline plugin */
pipeline {
  /*  agent { docker { image 'python:3.10.7-alpine' } }*/
   agent { 
        node {
            label 'docker-agent-python'
            }
      }
    stages {
        stage('build') {
            steps {
               /* sh 'python --version'*/
                echo "Pipeline test"
            }
        }
    }
}
