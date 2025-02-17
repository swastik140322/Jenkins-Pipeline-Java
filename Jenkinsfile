pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/swastik140322/Jenkins-Pipeline-Java.git' // Replace with your repo
            }
        }

        stage('Compile Java Code') {
            steps {
                sh 'javac src/HelloWorld.java'
            }
        }

        stage('Run Java Application') {
            steps {
                sh 'java -cp src HelloWorld'
            }
        }
    }
}
