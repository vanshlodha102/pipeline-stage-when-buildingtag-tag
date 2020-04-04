pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				     tag "release-*"
			}
		
            steps {                
                echo 'Hello from vash first time building tag'
            }
        }
    }
}
