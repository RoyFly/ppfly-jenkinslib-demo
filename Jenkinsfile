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
		//下载代码
        stage("testPrintMes"){
            steps{
                script{
                    mytools.PrintMes("测试输出日志的信息，带颜色",'green')
                    hello.call()
                }
            }
        }
	}
}