  pipeline {
        agent any
           stages {
              stage('Build') { 
                 steps { 
                    sh 'python app.py' 
            }
        }
        stages {
            stage('Test') {
                steps {
                    echo 'Hello World ...'
                }
            }
        }
    }
 
