properties([pipelineTriggers([cron('* * * * *')])])
pipeline {
    agent any

    stages {
        stage('Stage 1') {
            steps {
                sh '''
                    ls -l
                    python3 hi.py
                   '''
            }
        }
    }
}
