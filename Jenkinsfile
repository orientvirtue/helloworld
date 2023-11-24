pipeline {

    agent any

    stages {

        stage('Test') {
            steps {
				echo 'Testing'
            }
        }
 
    }
    post {
        // Clean after build
        always {
            cleanWs()
        }
    }
}
