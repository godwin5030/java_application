pipeline {
    
    stages {
        stage('Back-end') {
            agent {
                docker1 { image 'maven:3-alpine' }
            }
            
            steps {
                sh 'mvn --version'
            }
        }
        
    }
}
