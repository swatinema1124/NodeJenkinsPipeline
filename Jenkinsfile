pipeline {
         agent any
         stages {
                 stage('Build') {
                 steps {
                     
                    sh docker-compose up
                     
                 }
                 }
                 stage('Test') {
                 steps {
                    input('Do you want to proceed?')
                 }
                 }
}
}
