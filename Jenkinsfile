pipeline {
    agent any
    environment {
        PATH = "/opt/maven/bin:$PATH"
    }
    stages {
        stage('git clone') {
            steps {
                git url: 'https://github.com/pvrrk2005/sparkjava-war.git', branch: 'main'
                
            }
        }
        
        stage('build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}     // 1  // Ends the pipeline block
