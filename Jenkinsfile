pipeline {
    agent any

    stages {
        stage('Run python code') {
            steps {
                sh 'python --version'
                sh 'python hello-world.py'
            }
        }

//        stage('Unit Test') {
//            steps {
////                sh "mvn test"
//                echo "Unit Test"
//            }
//        }

//        stage('Functional Test') {
//            steps {
//                echo "Running functional test"
//            }
//        }

//        stage('package jar') {
//            steps {
////                sh 'mvn clean package'
//                echo "Packaging jar"
//
//            }
//        }
    }
}