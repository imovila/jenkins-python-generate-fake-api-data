pipeline {
  agent any
  stages {
	  stage('Build') {
		  steps {
			  script {
				  sh '/usr/bin/python3 get-fake-data.py'
			  }
		  }
	  }
  }
}
