pipeline {
     agent any
     tools {
            nodejs "nodejs"
         
           }
     environment {
            CI = 'true'
        }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
                sh 'mongo'
            }
        }
        stage('Test') {
              steps {
                 sh 'npm start'
            }
        }
               

    }
}
