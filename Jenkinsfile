pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Compiling the java source code'
                sh 'javac Hello.java'

            }
        }

    stage('run') {
        steps{
            echo 'Running thr compiled java code.'
            sh 'java Hello'
        }
      }
    }
}