pipeline {
    agent any
    parameters {
    	string(name: 'Appname' , defaultValue: 'ITA -static- ', description: 'input for veracode')
	}
    stages {
        stage('appname') {
            steps {
	    	script {
			def appname = "${params.Appname}"
		    	def appdir = appname.replace(" " , "_" )
	    		println "${appdir}"
	    		println "${appname}"
			}
            	}	
        }
    }
}
