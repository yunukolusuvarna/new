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
			echo 'mvn install'
		}
	}	
 stage('Build') {
		steps {
			echo 'mvn install'
		}
	}	
	stage('Deploy') {
	   steps {
	        echo 'echo deploying application '
	    }
	}
}
}
