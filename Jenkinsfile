pipeline {
    agent any 
    stages {
        stage('Master branch') { 
            steps {
                sh 'echo "This is master multi branch code testing yo"'
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
