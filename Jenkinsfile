@Library('my-shared-library') _

pipeline {
    agent any

    stages {
        
        
        stage('Checkout') {

            //when{ expression{params.action == 'create'}}

            steps {
            gitCheckout(
                branch: "main",
                url: "https://github.com/vishwajitkumar5/java_app.git"
                )
               // checkout([$class: 'GitSCM', branches: [[name: '*/main']], userRemoteConfigs: [[url: 'https://github.com/vishwajitkumar5/mrvishu_java_app.git']]])
            }
        }
    }
}