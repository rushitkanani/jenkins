pipeline{
	// agent any
	agent {docker {image 'maven:3.6.3'}}
	stages {
		stage('Build'){
			steps{
				echo "mvn --version"
			}
		}
	
		stage('Test'){
			steps{
				echo "Test"
			}
		}
		stage('Integration test'){
			steps{
				echo "Integration test"
			}
		}
	}
	post{
		always{
			echo 'Im awesome. I run always'
		}
		success {
			echo 'I run when you are sucessful'
		}
		failure {
			echo 'I run when you fail'
		}
	}
}


