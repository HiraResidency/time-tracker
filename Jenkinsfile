pipeline {
    agent any

    stages {
        stage('Build') 
		{
            steps 
			{
                echo 'Build Application'
            }
        }
		stage('Test') 
		{
            steps 
			{
                echoo 'Test Application'
            }
        }
		stage('Deploy') 
		{
            steps 
			{
                echo 'Deploy Application'
            }
        }
    }
	post
	    {
	          always{
			  bat 'hello'
                          build 'DevProject1'
	       }
	}
}
