/*Jenkinsfile (Declarative Pipeline) */
/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'docker-slave-test' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
