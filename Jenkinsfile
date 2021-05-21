pipeline {
	agent { docker { image 'nginx:latest'} }
	stages {
             stage ('Build') {
		steps {
			sh 'nginx -v'
		 	echo "Build"
		}
	     }
             stage('Test') {
		steps {
			echo "Test"
		}
             }
	     stage('Integration-Test') {
		steps {
	                echo "Integration Test"
		}
	     }
       }
}
