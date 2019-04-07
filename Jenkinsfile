pipeline {
    agent any
    stages {
        stage('appname') {
            steps {
	    	script {
			def appname = "test"
		    	def appdir = appname.replace(" " , "_" )
	    		println "${appdir}"
	    		println "${appname}"
			}
            	}	
        }
    }
}
