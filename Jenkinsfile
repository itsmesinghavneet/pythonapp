pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
               echo 'test is being done'
            }
        }
        stage('Test'){
            steps {
                echo 'test is being done'
            }
        }
        stage('Deploy') {
            steps {
                sh 'make publish'
            }
        }
    }
}
