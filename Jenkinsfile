pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
                sh '''
                    echo "Hello World!"
                    echo "Multiline shell steps work too"
                    ls -lah
                    '''
            }
        }
    }
}
