pipeline {
    agent any
    
    stages {
        stage('Git clone') {
            steps {
                git 'https://github.com/santy1896/jen_react_test.git'
                
                dir('jen_react_test')
        }
    }
        stage('Build') {
            steps {
                sh 'npm i'
            }
        }
        stage('Start') {
            steps {
                sh 'npm start'
            }
        }
    }
}
