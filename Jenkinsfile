pipeline {

    agent any

    stages {

        stage("build"){
            steps {
                echo 'building the application...'
                // sh 'npm install --force'
                // sh 'npm build'
            }
        }
        stage("test"){
            steps {
                echo 'testing the application...'
            }
        }
        stage("deploy"){
            steps {
                echo 'deploying the application...'
            }
        }
    }
}