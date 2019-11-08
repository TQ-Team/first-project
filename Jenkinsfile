pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                echo "${env.BRANCH_NAME}"
                script {
                    if(env.BRANCH_NAME=="develop"){
                        println "hello world"
                        sh 'ls -la'
                    }
                }
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
