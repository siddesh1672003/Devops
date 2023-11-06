pipeline{
    agent any
    
    stages{
        stage('Build'){
            steps{
                echo 'Build application'
            }
        }
        stage('Test'){
            steps{
                echo 'Test app'
            }
        }
        stage('Deploy'){
            steps{
                echo 'Deploy app'
            }
        }
    }
    post 
    {
    
    always{
        emailext body: 'summary', subject: 'Pipeline syntax', to: 'patilsiddeshb16@gmail.com'
        
    }    
    }
    
}