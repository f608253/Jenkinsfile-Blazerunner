pipeline {
	agent any
	stages {
		stage ('build') {
		     steps {	  
			sh 'echo "A one line step"'
			sh ''' 
			echo "A multiline step"'
			cd /tests/results
			ls -lrt
			'''
			}
		}
	}
}
