pipeline {
	//agent any
	agent { docker { image 'maven:3.6.3'}}
	stages {
		stage ('Build') {
			steps {
				echo "Build"
			}
		}
		stage ('Test') {
			steps {
				echo "Test"
			}
		}
		stage ('Integration test') {
			steps {
				echo "Integration test"
			}
		}
	}
}