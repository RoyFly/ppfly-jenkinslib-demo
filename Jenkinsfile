@Library('ppfly-jenkinslib-demo') _
def tools = new org.devops.tools()
pipeline {

	agent { label  "master" }

	stages {
		stage("build"){
			steps{
				script{
					msg = "hello jenkins"
					tools.PrintMsg(msg)
				}
			}
		}
	}
}

