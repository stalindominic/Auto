pipeline {
    agent any

    stages {
        stage('Hello h') {
            steps {
                sh 'mkdir /temp/test1'
                sh 'cd /temp/test1'
                sh 'touch one'  
                sh 'cp -r /temp/test1/one /tmp'
                echo 'welcome India'
            }
        }
    }
}
