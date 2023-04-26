pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh 'cd /temp' 
                sh 'mkdir test1'
                sh 'cd /temp/test1'
                sh 'touch one'  
                sh 'cp -r /temp/touch /tmp'
                echo 'welcome India'
            }
        }
    }
}
