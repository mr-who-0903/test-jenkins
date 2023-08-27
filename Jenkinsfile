pipeline{
	agent any
	stages{
		stage("testing sh"){
			steps{
				echo "testing sh.."
				def _out = sh(script: "pwd", returnStdout: true)
				println "Output = ${_out}"
			}
		}
		
	}
}
