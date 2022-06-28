pipeline {
    agent any

    stages {
        stage('first') {
            parallel{
         	    stage('first A'){
	            steps {
                    echo 'Hello World'
                    } 
                    }
	            stage('first B'){
	            steps{
	            echo 'sample'
	            }
                    } 
            }  
        } 
    }    
}
