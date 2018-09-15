pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Heloo World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
