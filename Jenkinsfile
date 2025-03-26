pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                echo "hi"
                sh '''#!/bin/bash
                 touch /tmp/test.txt
                '''
            }
        }
        stage('Test') { 
            steps {
            echo "hello"
            }
        }
        stage('Deploy') { 
            steps {
                echo "hi-2"
            }
        }
    }
}
