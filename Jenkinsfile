pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh '''
                echo "this is a test" > ab.txt
                '''
            }
        }
    }
}
