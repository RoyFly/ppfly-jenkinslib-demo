@Library('jenkinslib') _
def mytools = new org.devops.tools()
pipeline {

	agent any

	stages {
		stage("build"){
			steps{
				script{
					msg = "hello jenkins"
					mytools.PrintMsg(msg)
				}
			}
		}
	}
}