pipeline{
	agent any
	stages{
		stage("create file"){
			steps{
				echo "Creating a test file"
				sh "cd C:/Users/DELL/Desktop"
				sh "touch jenkins_test.txt"
			}
		}
		stage("test"){
			steps{
				echo "testing the application"
			}
		}
		stage("deploy"){
			steps{
				echo "deploying the application"
			}
		}
		
	}
}
