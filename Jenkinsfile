pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                sh 'python app.py' 
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
