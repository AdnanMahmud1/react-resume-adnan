pipeline {

    agent any

    stages {

        stage("build"){
            steps {
                 sh 'npm install --force'
                 sh 'npm run build'
                echo 'building the application...'
                echo 'Application builing'

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