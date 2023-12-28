pipeline {
    agent any
    }
    stages{
        stage('git-checkout'){
            steps{
                checkout([$class: 'GitSCM',
                          branches: [[name: '*/main']], // Branch to checkout
                          userRemoteConfigs: [[url: 'https://github.com/srijyothsna5354/devops-automation/tree/main']]]) // Git repository URL
            }
            }
        }
        
        }
       
        }
