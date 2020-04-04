pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				     tag "2.0"
			}
		
            steps {                
                echo 'Hello from vash first time building tag'
            }
        }
    }
}
