pipeline {
    agent any
    stages {
        stage('Hello!') {
            steps {
                echo 'Hello World'
            }
        }
        stage('See you!') {
            steps {
                echo 'Goodbye World'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
        }
    }
}
