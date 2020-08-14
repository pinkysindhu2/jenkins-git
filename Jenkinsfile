pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat "sh -c 'echo "Hello World"'"
                bat ''' sh -c
                    "echo "Multiline shell steps works too""
                    ls -lah
                '''
            }
        }
    }
}
