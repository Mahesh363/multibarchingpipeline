ipipeline {   
    agent any

    stages {   
        stage('sprint branch') { 
            steps { 
               sh 'echo "This is sprint branch"' 
            }
        }
     
        stage('sprint1') { 
            steps { 
               sh 'echo "sprint1 application..."'
            }
        }

        stage("Deploy application") { 
             steps { 
                sh 'echo "Deploying application..."'
            }
        }  
    }
}
