pipeline {
    agent any
    tools{
        maven "Maven3.6.0"
        jdk "jdk1.8.0_202"
    }
    stages {
        stage('Build') {
            steps {
                sh 'printenv'
                sh 'which java &&which mvn'
                sh 'java -version'
                sh 'mvn -version'
                //sh 'rm -rf ./* &&  rm -rf ../../.m2/*'
            }

        }
    }
}
