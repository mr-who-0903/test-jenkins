pipeline{
	agent any
	stages{
		stage("testing sh"){
			steps{
				script{
					echo "testing sh.."
					def _out = sh(script: 'pwd', returnStatus: true)
					println "Output = ${_out}"
				}
			}
		}
		
	}
}
