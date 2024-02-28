pipeline {
    agent any
    environment {
        NODEJS_HOME = tool 'NodeJS'
        PATH = "$PATH:$NODEJS_HOME/bin"
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}