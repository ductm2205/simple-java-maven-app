pipeline {
	agent {
		label 'demo-agent'
	}
	tools {
		maven 'maven-3'
	}
	stages {
		stage('Build') {
			steps {
				sh 'mvn -B -DskipTests clean package'
			}
		}
	}
}
