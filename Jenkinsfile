pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
               echo'build is being done'
                sh 'python app.py'
               
            }
        }
        stage('Test'){
            steps {
                echo 'test is being done'
                sh '''
                ./my_script.sh &
                        PID=$!
                            sleep 2
                    kill $PD 
                    ''' 
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy is being done'
            }
        }
    }
}
