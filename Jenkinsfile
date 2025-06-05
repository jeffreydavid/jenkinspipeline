pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'This is build stage'
                touch /tmp/buildfile.txt
            }
        }
      stage('test') {
            steps {
                echo 'This is test stage'
                touch /tmp/testfile.txt
            }
        }
      stage('deploy') {
            steps {
                echo 'This is deploy stage'
                touch /tmp/deployfile.txt
            }
        }
    }
}
