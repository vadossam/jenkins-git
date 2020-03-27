pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh 'pwd; echo; ip a'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
                sh 'ls -lah ..'
                sh 'ls -lah ..'
            }
        }
    }
}
