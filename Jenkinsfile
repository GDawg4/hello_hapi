#!/usr/bin/env groovy

pipeline {

    agent {
        docker {
            image 'nginx'
            args '-p 80:80 -d'
        }
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
    }
}
