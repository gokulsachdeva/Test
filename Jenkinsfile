
pipeline {
     agent any 
        stages {	
		stage ('checkout') {
         steps {
	   echo "checkout from github";
	     git credentialsId: '9dea2dc1-194b-4b22-953f-d0b1cdb39dad', url: 'https://github.com/gokulsachdeva/test.git'
	  }
	 }
	 stage ('test') {
         steps {
	 
	   echo "Test the code quality";
	   }
	  }
	stage ('build') {
         steps {
	 
	   echo "build the code";
	   
	   }
	 }

	stage ('Deploy') {
         steps {
	 
	   echo "Deploy the code to test server";
	   }
	}
  }
}
