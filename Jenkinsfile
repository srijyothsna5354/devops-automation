pipeline {
    agent any
    tools{
        maven 'maven 3.9.5'
    }
    stages{
        stage('Build Maven'){
            steps{
                checkout([$class: 'GitSCM',
                          branches: [[name: '*/main']], // Branch to checkout
                          userRemoteConfigs: [[url: 'https://github.com/username/repository.git']]]) // Git repository URL
            }
            }
        }
        
        }
       
        }
