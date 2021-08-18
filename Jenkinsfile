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
                sh 'npm start'
                
            }
        }
        stage('Test') {
              steps {
                 echo "done"
            }
        }
               

    }
}
