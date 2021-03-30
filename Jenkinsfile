pipeline {
	agent any
	stages {
		stage('Build'){
			steps {
				echo "Build"
			}
		}
		stage('Test') {
			steps {
				echo "Test"
			}
		}
		stage('Integration Test') {
			steps {
				echo "Integration Test"

			}
		}
	} 
	post {
		always {
			echo 'Im awesome. I run always'
		}
		sucess {
			echo 'I run when you are sucessful'
		}
		fail {
			echo 'I run when you are failful'
		}
	}
}

