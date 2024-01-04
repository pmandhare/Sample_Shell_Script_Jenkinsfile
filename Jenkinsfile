pipeline {
    agent any
    stages {
        stage('first') {
            steps {
                echo "executing script"
                sh 'chmod +x ./mydate.sh'
                sh './mydate.sh'
            }
        }
    }
}
