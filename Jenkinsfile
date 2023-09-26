pipeline {
    agent any 


    stages {
        stage('Dependencies') {
            steps {
                echo 'Fetching dependencies...'
               
            }
        }
    }
        stage('Test') {
            steps {
                echo 'Running tests...'
               
            }
        }

        
            
        

 
         


        stage('Package') {
            steps {
                echo 'Packaging the binary...'
              
            }
        }

        stage('Cleanup') {
            steps {
                echo 'Cleaning up...'
               
            }
        }
    

    post {
        always {
            echo 'This will always run'
        }
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed :('
        }
    }
}

