pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'ant -f build.xml -v'
		sh 'docker run hello-world'
            }
        }
    }
}
