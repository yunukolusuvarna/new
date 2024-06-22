pipeline {
    agent any

    stages {
       stage('Clone-Repo') {
	  steps {
	        	git url: 'https://github.com/yunukolusuvarna/new.git',
				branch: 'master'
	    	}
        }
	stage('Build') {
		steps {
			echo 'mvn building'
		}
	}	
       stage('test') {
		steps {
			echo 'mvn testing'
		}
	}	
	stage('Deploy') {
	   steps {
	        echo 'echo deploying application '
	    }
	}
}
}
