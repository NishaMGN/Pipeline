pipeline {
	agent any
	stages {
    	stage('Build') {
	    	steps {
		    	sh 'echo Stage 1 : This is build stage '
			}
		}
    	stage('Test') {
	    	steps {
		    	sh 'echo Stage 2 : This is Test stage '
			}
		}
	    stage('Deploy') {
		    steps {
			    sh 'echo Stage 3 : This is Deploy stage '
			}
		}
	}
}