pipeline {
    agent any
    
    stages {
        stage('Print PWD') {
            steps {
                script {
                    // Use bat instead of sh for Windows
                    def pwd = bat(script: 'echo %cd%', returnStdout: true).trim()
                    echo "Current Working Directory (PWD): ${pwd}"
                }
            }
        }
    }
}
