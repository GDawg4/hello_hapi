#!/usr/bin/env groovy

pipeline {

    agent {
        docker {
            image 'nginx'
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
