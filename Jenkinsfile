Jenkinsfile (Declarative Pipiline)
pipeline {
	agent { docker 'php' }
	stages {
		stage('build') {
			steps {
				sh 'php --version'
			}
		}
	}
}
