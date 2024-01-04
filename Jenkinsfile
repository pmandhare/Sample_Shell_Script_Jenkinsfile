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
    }
    stages {
        stage('test') {
            steps {
                echo "this is tesing "
            }
        }
    }
    stages {
        stage('deploy') {
            steps {
                echo "deploying"
            }
        }
    }
}
