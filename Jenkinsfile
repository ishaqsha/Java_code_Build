pipeline {
  agent any  
    stages {
        stage('clean') { 
            steps {
                sh 'mvn clean install -DskipTests'
            }
        }
        stage('test') { 
            steps {
               echo "doing test"
            }
        }
        stage('Deploy') { 
            steps {
                echo "I am not deploying anything"
                sh 'mvn deploy'
            }
        }
    }
}
