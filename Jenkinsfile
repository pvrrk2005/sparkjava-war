pipeline {
    agent any
    environment {
        PATH = "/opt/maven/bin:$PATH"
    }
    stages {          
        stage('my-build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}     
