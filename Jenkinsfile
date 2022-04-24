pipeline {
    agent any
    tools{nodejs"nodejs"}
    stages {
        stage('Dev') {
            steps {
               git 'https://github.com/wilson7875/aws_codebuild_codedeploy_nodeJs_demo.git'
               echo "check my content"
               sh 'cat index.js'
            }
        }
        stage('build') {
            steps {
                sh 'npm install'
            }
        }
    }
}