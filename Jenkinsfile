pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                echo "Compiling source code"
            }
        }

        stage('Unit Test') {
            steps {
//                sh "mvn test"
                echo "Unit Test"
            }
        }

        stage('Functional Test') {
            steps {
                echo "Running functional test"
            }
        }

        stage('package jar') {
            steps {
//                sh 'mvn clean package'
                echo "Packaging jar"

            }
        }
    }
}