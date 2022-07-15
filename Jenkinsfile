pipeline {
         agent any
         stages {
                 stage('Build') {
                 steps {
                    sh '/usr/local/bin/docker-compose.yaml up --build'
                 }
                 }
                 stage('Test') {
                 steps {
                    input('Do you want to proceed?')
                 }
                 }
}
}
