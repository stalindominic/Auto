pipeline {
    agent any

    stages {
        stage('Hello h') {
            steps {
                sh 'cd /temp' 
                sh 'mkdir /temp/test1'
                sh 'cd test1'
                sh '/temp/test1/touch one'  
                sh 'cp -r /temp/touch /tmp'
                echo 'welcome India'
            }
        }
    }
}
