pipeline {
    agent {
        docker {
            image 'gradle:8.14-jdk21'
        }
    }
    stages {
        stage('build') {
            steps {
                sh 'whoami'
                sh 'pwd'
                sh 'cd /var/jenkins_home'
                sh 'pwd'
                
                sh 'touch it_works.txt'
            }
        }
    }
}