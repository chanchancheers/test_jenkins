pipeline {
    agent any

    stages {
        stage('test') {
            steps {
                sh '''
                    whoami
                    pwd
                    touch it_works.txt
                    ls -al
                '''
                
                sh 'exit 1'
            }
        }
    }
}