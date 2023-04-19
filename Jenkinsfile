pipeline {
    agent any 
    tools {
        maven "Maven2"
    }
    stages {
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
