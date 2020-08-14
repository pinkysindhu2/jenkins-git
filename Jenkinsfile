pipeline {
    agent any
    stages{
        stage('Build'){
            steps{
                bat ''' sh -c 'echo "Hello"' '''
                bat ''' sh -c 'echo "Multiline shell steps works too"'
                    sh -c 'ls -lah'
                '''
            }
        }
    }
}
