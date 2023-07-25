pipeline {
    agent any

    stages {
        stage("check ci skip") {
            steps {
                scmSkip(deleteBuild: true, skipPattern:'.*\\[ci skip].*')
            }
        }
    
        stage("test") {
            steps {
                sh "export"
            }
        }
    }
}
