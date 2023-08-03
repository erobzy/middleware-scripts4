 pipeline {
    agent any

    stages{
        stage("build"){
            steps{
                sh 'zip middlewareScript-${BUILD_NUMBER}.zip * --exclude Jenkinsfile README.md'  
            }
        }
    }
}