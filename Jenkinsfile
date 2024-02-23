pipeline {
  agent any
  stages
   {
         stage("GIT")
	 {
           steps
		{
		git "https://github.com/Lalit280/pipeline_jenkins.git"
		}
	 }
	 stage("RUN")
         {
           steps
		{
		sh "demo.java"
		sh "main.py"
		}
	 }
   }
}
