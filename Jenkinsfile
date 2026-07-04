pipelione {
    agent { docker { image 'gradle:8.14-jdk21' } }
    stages {
        stage('build') {
            steps {
                sh './gradle build'
            }
        }
    }
}