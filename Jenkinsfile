// Declarative pipeline
pipeline {
agent any
stages {
	stage('Build') {
		steps{
		
		echo "Build"
		echo "$PATH"
		echo "BUILD_NUMBER - $env.BUILD_NUMBER"
		echo "BUILD_TAG - $env.BUILD_TAG"
		}
	}
	stage('Test') {
		steps{
		echo "Test"
		}
	}
	stage('Integration Test') {
		steps{
		echo "Integration Test"
		}
	}
}
}
