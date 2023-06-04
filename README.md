pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage ('open'){
            steps {
                echo "me"
    }
}

