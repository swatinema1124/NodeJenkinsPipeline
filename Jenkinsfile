pipeline {
         agent any
         stages {
                 stage('Build') {
                 steps {
                    sh '/usr/local/bin/docker-compose up --build'
                 }
                 }
                 stage('Test') {
                 steps {
                    input('Do you want to proceed?')
                 }
                 }
 }
