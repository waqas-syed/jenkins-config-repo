pipeline {
	agent { label 'master' }
    stages {
        stage('build') {
            steps {
				build 'Template_Project'
                echo 'Pipeline project build step'
            }
        }
    }
}