pipeline {
         agent any
         stages {
                 stage('Build') {
                 steps {
                    sh '.docker-compose up --build'
                 }
                 }
                 stage('Test') {
                 steps {
                    input('Do you want to proceed?')
                 }
                 }
}
}
