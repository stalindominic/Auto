pipeline {
    agent any

    stages {
        stage('Hello h') {
            steps {
                sh 'mkdir test1'
                sh 'cd test1'
                sh 'touch one.txt'
                sh 'cp -r test1/one /tmp'
                echo 'welcome India'
            }
        }
    }
}
