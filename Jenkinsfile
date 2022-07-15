pipeline {
         agent any
         stages {
                 stage('Build') {
                 steps {
                    sh docker-compose -f docker-compose.yml build
                 }
                 }
                 stage('Test') {
                 steps {
                    input('Do you want to proceed?')
                 }
                 }
}
}
