pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh '''
                    ls -l
                    python3 hi.py
                   '''
            }
        }
    }
}
