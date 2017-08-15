pipeline {
    agent { docker 'php' }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}


/* Jenkinsfile (Scripted Pipeline) */
/* Requires the Docker Pipeline plugin */
/*
node('docker') {
    checkout scm
    stage('Build') {
        docker.image('php').inside {
            sh 'php --version'
        }
    }
}
*/