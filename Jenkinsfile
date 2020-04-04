pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				     buildingTag()
			}
		
            steps {                
                echo 'Hello from vash first time building tag'
            }
        }
    }
}
