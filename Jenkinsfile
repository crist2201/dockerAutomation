pipeline {
	 agent any
	 stages {
		 stage("buildDocker") {
			 steps {
				 bat 'docker build -t automationjenkins:1.0.0 .'
			 }
		 }
		 stage("runDocker") {
			 steps {
				 bat 'docker run automationjenkins:1.0.0'
			 }
		 }
	 }
 }
