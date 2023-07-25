pipeline {
    agent any

    stages {
        stage("check ci skip") {
            steps {
                scmSkip(deleteBuild: false, skipPattern:'.*\\[ci skip].*')
            }
        }
     
        stage("test") {
            steps {
                sh "export"
            }
        }
    }
}
