pipeline {
    agent any
    //triggers {
	//cron ('* * * * *')
	//}
    stages {
	stage('Git checkout') {			
	    steps {
	         git 'https://github.com/abhi6666/Java-repository.git'
	    }
        }    
	stage('Build') {			
	    steps {
	         echo "Building the application"
	    }
        }
		
	stage('Test') {			
	    steps {
     		echo "Testing the application"
	    }
        }
		
	stage('Deploy') {			
	    steps {
		echo "Deploying the application"
	    }
        }
		
    }
	
}
