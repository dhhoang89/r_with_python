/*Jenkinsfile (Declarative Pipeline) */
/* Requires the Docker Pipeline plugin */
pipeline {
    agent { 
        node {
            label 'docker-slave-test'
            }
    }
    stages {
        stage('build') {
            steps {
                sh 'python3 --version'
            }
        }
    }
}
