pipeline {
    agent any 
    tools {
        maven "Maven3"
    }
    stages {
        stage('clone') { 
            steps {
                git 'https://github.com/ExlearnTechnologies/Hello-World-SpringBoot.git'
            }
        }
        stage('Compile') { 
            steps {
                sh 'mvn compile'
            }
        }
        stage('Test') { 
            steps {
                sh 'mvn test'
            }
        }
        stage('Package') { 
            steps {
                sh 'mvn package'
            }
        }
        stage('Deploy') { 
            steps {
                sh 'echo "Deployement Successfull"'
            }
        }
    }
}
