pipeline {
    agent any
    
    stages {
        stage('Display Info') {
            steps {
                echo "JENKINS_URL: ${env.JENKINS_URL}"
                echo "BUILD_ID: ${env.BUILD_ID}"
            }
        }
    }
}
