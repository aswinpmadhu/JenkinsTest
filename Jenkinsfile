pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too OK"
                    ls -lah
                '''
                input "Does the staging environment look ok?"
            
            }
        }
    }
}
