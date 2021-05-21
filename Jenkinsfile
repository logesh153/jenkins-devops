pipeline {
	agent { label 'my-pipe' docker 'nginx:1.19.10' }
	stages {
             stage ('Build') {
		steps {
			sh 'nginx -v'
		 	echo "Build"
		}
	     }
       }
}

