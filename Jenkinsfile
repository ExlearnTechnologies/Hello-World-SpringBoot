pipeline {
    agent any 
    tools {
        maven "Maveen3"
    }
    stages {
        stage('Compile') { 
            steps {
                git 'https://github.com/ExlearnTechnologies/Hello-World-SpringBoot.git'
                sh 'mvn compile'
            }
        }
        stage('Test') { 
            steps {
                git 'https://github.com/ExlearnTechnologies/Hello-World-SpringBoot.git'
                sh 'mvn test'
            }
        }
        stage('Package') { 
            steps {
                git 'https://github.com/ExlearnTechnologies/Hello-World-SpringBoot.git'
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
