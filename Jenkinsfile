pipeline {
	agent any
	stages {
		stage ('build') {
		     steps {	  
			sh 'echo "A one line step"'
			sh ''' 
			echo "A multiline step"
			cd $HOME
			pwd
			ls -lrt
			make
			df -h
			ping -c4 google.co.in
			'''
			}
		}
	}
}
