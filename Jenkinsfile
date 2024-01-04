pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "executing script"
                sh 'chmod +x ./mydate.sh'
                sh './mydate.sh'
            }
        }
        stage('test') {
            steps {
                echo "this is testing"
            }
        }
        stage('deploy') {
            steps {
                echo "deploying"
            }
        }
    }
}
