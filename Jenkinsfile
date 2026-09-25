pipeline {
    agent any

    stages {
        stage('Compile Code') {
            steps {
                echo 'Compiling Java file...'
                sh 'javac Main.java'
            }
        }
        stage('Run Code') {
            steps {
                echo 'Running Java application...'
                sh 'java Main'
            }
        }
    }
}
