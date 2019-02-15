pipeline {
    agent none
    stages {
        stage('build') {
            agent { label 'epbuild18' }
            steps {
                sh 'uname'
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
                bat 'batchfile'
            }
        }
    }
}
