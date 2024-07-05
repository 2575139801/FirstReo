pipeline {
    agent any

    stages {
         stage('test pull gitee code') {
            steps {
                git 'https://gitee.com/schq/jenkins-test.git'
                echo 'test pull code'
            }
        }
        
        stage('test maven') {
            steps {
                
                 sh 'mvn --version'
            }
        }
        
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
