pipeline {
    agent { label "nhaug" }
    stages {
        stage("start") {
            steps {
                echo "jetzt wirklich"
            }
        }
    }
    post {
        always {
            sh 'printenv'
        }
    }
}
