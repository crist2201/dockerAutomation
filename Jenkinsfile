pipeline {
	 agent any
	 stages {
		 stage("buildDocker") {
			 steps {
				 bat 'docker build -t automationJenkins:1.0.0 .'
			 }
		 }
		 stage("runDocker") {
			 steps {
				 bat 'docker run automationJenkins:1.0.0'
			 }
		 }
	 }
 }
