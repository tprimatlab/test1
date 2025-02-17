pipeline {
    agent any
    
    stages {
        stage('Print PWD') {
            steps {
                script {
                    // Print the current working directory (PWD)
                    def pwd = sh(script: 'pwd', returnStdout: true).trim()
                    echo "Current Working Directory (PWD): ${pwd}"
                }
            }
        }
    }
}
