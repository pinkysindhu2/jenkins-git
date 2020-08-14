pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat "sh 'echo "Hello World"'"
                bat ''' sh "
                    echo "Multiline shell steps works too"
                    ls -lah
                " '''
            }
        }
    }
}
