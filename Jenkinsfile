pipeline {
    agent {
        docker {
            image 'gradle:8.14-jdk21'
        }
    }
    stages {
        stage('build') {
            steps {
                sh 'cd /var/jenkins_home && touch it_works.txt'
            }
        }
    }
}