pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo '=== BUILD STAGE ==='
                pwd
                ls -la
                touch build.txt
            }
        }

        stage('Test') {
            steps {
                echo '=== TEST STAGE ==='
                ls -la
                mv build.txt test.txt
            }
        }

        stage('Deploy') {
            steps {
                echo '=== DEPLOY STAGE ==='
                echo 'Simulating deployment'
                ls -la
            }
        }
    }
}
