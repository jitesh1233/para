pipeline {
    agent any
    stages {
        parameters {
  choice choices: ['Build', 'Test', 'Deploy'], description: 'will pick any one', name: 'jitesh'
}
        stage('Build') {
            steps {
                echo '${param.jitesh}'
            }
        }
        stage('Test') {
            steps {
                echo '${param.jitesh}'
            }
        }
        stage('Deploy') {
            steps {
                echo '${param.jitesh}'
            }
        }
    }
}
