pipeline {
	agent any
	stages {
		stage ('build') {
			echo "This is for build"
		}
		stage ('test: integration-&-quality') {
			echo "test: integration-&-quality"
		}
		stage ('test: functional') {
			echo "test: functional"
		}
		stage ('approval') {
			echo "Approval"
		}
		stage ('deploy:prod') {
			echo "deploy:prod"
		}
	}
}
