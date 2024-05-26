pipeline {
    agent any
    stages {
        parameters {
  choice choices: ['Build', 'Test', 'Deploy'], description: 'will pick any one', name: 'jitesh'
}
        stage('Build') {
            steps {
                echo "this is build: ${param.jitesh}"
            }
        }
        stage('Test') {
            steps {
                echo "$this is test: {param.jitesh}"
            }
        }
        stage('Deploy') {
            steps {
                echo "this is deply: ${param.jitesh}"
            }
        }
    }
}
