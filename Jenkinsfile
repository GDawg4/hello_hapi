#!/usr/bin/env groovy

pipeline {

    agent {
        docker {
            image 'nginx'
            args '--name mynginx1 -p 80:80 -d nginx'
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
