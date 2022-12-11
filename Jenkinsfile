pipeline{
    tools{
        maven 'mymvn'
    }
    
    agent any
    
    stages{
        stage('ImportRepo'){
            steps{
                echo 'Pipeline Begins Here !!!!'
                git 'https://github.com/KRISSBAJO/onlinebookstore.git'
            }
        }
    }
}
