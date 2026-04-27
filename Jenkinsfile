pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo '=== BUILD STAGE ==='
                sh 'pwd'
                sh 'ls -la'
                sh 'touch build.txt'
                sh 'echo "Build complete"'
            }
        }

        stage('Test') {
            steps {
                echo '=== TEST STAGE ==='
                sh 'ls -la'
                sh 'mv build.txt test.txt'
                sh 'echo "Test complete"'
            }
        }

        stage('Deploy') {
            steps {
                echo '=== DEPLOY STAGE ==='
                sh 'ls -la'
                sh 'echo "Deployment simulation complete"'
            }
        }
    }
}
