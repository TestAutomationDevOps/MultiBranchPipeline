pipeline
{
	agent any
	
    	stages
    	{
        	stage('Checkout Code')
        	{
              		steps
              		{
                  		echo "Git Checkout is Successful"
              		}
        	}

		stage('Build')
		{
			steps
			{              
                  		echo "Build is Successful"
              		}
        	}
		
		stage('Sonarqube')
		{
			steps
			{               
                  		echo "Sonarqube is Successful"
              		}
        	}
		
		stage('Build Docker Image')
		{
			steps
			{      
                  		echo "Docker Image is Built Successfully"
            		}
        	}
		
		stage('Push Docker Image to DockerHub')
		{
			steps
			{      
                  		echo "Docker Image is Pushed to DockerHub Successfully"
            		}
        	}
		
		stage('Deploy Application')
		{
			steps
			{      
                  		echo "Application is Deployed Successfully"
            		}
        	}
    	}
}
