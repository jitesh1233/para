pipeline {
    agent any
    stages {
        parameters {
  choice choices: ['Build', 'Test', 'Deploy'], description: 'will pick any one', name: 'jitesh'
}
        stage('Build') {
            steps {
                echo '${jitesh}'
            }
        }
        stage('Test') {
            steps {
                echo '${jitesh}'
            }
        }
        stage('Deploy') {
            steps {
                echo '${jitesh}'
            }
        }
    }
}
