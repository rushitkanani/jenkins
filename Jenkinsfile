pipeline{
	agent any
	stages {
		stage('Build'){
			steps{
				echo "Build"
				echo "Test"
				echo "Integration test"
			}
		}
	}
	post{
		always{
			echo 'Im awesome. I run always'
		}
		sucess {
			echo 'I run when you are sucessful'
		}
		failure {
			echo 'I run when you fail'
		}
	}
}

