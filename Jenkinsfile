pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
            retry(3){
                sh 'echo "Hello World"'
                }
                sh '''
                    echo "Multiline shell steps works too"
                '''
            }
        }
    }
}