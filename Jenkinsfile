pipeline {
    agent { label "nhaug" }
    stages {
        stage("cleanup") {
            steps {
                echo "Vor clean"
                sh "ls -al"
                cleanWs()
                echo "Nach Clean"
                sh "pwd"
                sh "ls -al"
            }
        }
        stage("checkout") {
            steps {
                echo "jetzt muss checkout erfolgen"
            }
        }
        stage("start") {
            steps {
                echo "jetzt wirklich"
            }
        }
        stage("build") {
            steps {
                echo "build"
            }
        }
    }
    post {
        always {
            sh 'printenv'
        }
    }
}
