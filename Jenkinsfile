pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'cd /temp' 
                sh 'mkdir test'
                sh 'cd /temp/test'
                sh 'touch one'  
                sh 'cp -r /temp/touch /tmp'
                echo 'welcome India'
            }
        }
    }
}
