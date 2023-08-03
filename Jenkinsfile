 pipeline {
    agent any

    stages{
        stage("build"){
            steps{
                zip middlewareScript4-${BUILD_NUMBER}.zip * --exclude Jenkinsfile README.md
            }
        }
    }
}