pipeline {
    agent any

    stages {
        stage ('Compile Stage') {
	   steps {	
	    echo 'Clean previous build output'
	    sh './gradlew clean'
	   }	   
        }

    }

}
