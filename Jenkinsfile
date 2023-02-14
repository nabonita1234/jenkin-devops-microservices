// Declarative pipeline
pipeline {
agent any
stages {
	stage('Build') {
		steps{
		
		echo "Build"
		echo $PATH
		echo "BUILD_NUMBER - $env.BUILD_NUMBER"
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
