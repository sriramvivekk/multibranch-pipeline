pipeline {
    agent any 
    stages {
        stage('hotfix branch') { 
            steps {
                sh 'echo "This is hotfix branch code testing"'
            }
        }
        stage('Sprint1') { 
            steps {
                sh 'echo "sprint1 application..."'
            }
        }
        stage('Deploy application') { 
            steps {
                sh 'echo "Deploying application...."'
            }
        }
    }
}
