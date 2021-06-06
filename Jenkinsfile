pipeline {	 

	agent any	

	tools {

		maven 'mav'

		}

    	stages {     	 

    	stage("Compile") {          	 

            	steps {               	 

                	sh "mvn compile"          	 

            	}     	 

        	}     	 

    	stage("Unit test") {          	 

        	steps {               	 

                	sh "mvn test"          	 

            	}     	 

        	}	 

    	}

}


