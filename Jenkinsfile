pipeline {
    agent any
    }
tools{
maven 'maven 3.9.5'
I}
    stages{
        stage('git-checkout'){
            steps{
                git branch: 'main', url: 'https://github.com/srijyothsna5354/devops-automation.git'
                sh 'mvn clean install'
            }
           
            }
       
        }
        
        
       
        
