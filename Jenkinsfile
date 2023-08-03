 pipeline {
    agent any

    stages{
        stage("build"){
            steps{
                zip middlewareScript-${BUILD_NUMBER}.zip * --exclude Jenkinsfile README.md
            }
        }
    }
}