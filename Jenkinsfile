pipeline {
	agent { docker { image 'nginx:1.19.10 } }
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
