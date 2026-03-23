pipeline {
    agent any

    stages {
        stage('check out') {
            steps {
                echo 'checking out code'
                sh 'git clone git@github.com:weisha0515/git-test.git'
            }
        }
        stage('Jenkins') {
            steps {
                echo 'Hello Jenkins'
            }
        }
        stage('Job') {
            steps {
                echo 'Hello Job'
            }
        }
    }
}
