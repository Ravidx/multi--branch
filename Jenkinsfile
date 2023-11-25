pipeline {   
    agent any

    stages {   
        stage('prod branch') { 
            steps { 
               sh 'echo "This is prod branch"' 
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
