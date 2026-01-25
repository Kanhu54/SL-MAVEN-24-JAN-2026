pipeline
{
	agent any
		tools
		{
			maven 'MAVEN_HOME'
		}
		stages
		{
			stage('Welcome Stage')
			{
				steps
				{
					echo 'Welcome to Pipeline'
				}
				stages
		{
			stage('Welcome Stage by Kanhu')
			{
				steps
				{
					echo 'Welcome to Pipeline'
				}
			}
			stage('Clean Stage  By Kanhu')
			{
				steps
				{
					sh 'mvn clean'
				}
			}
			stage('Clean Stage')
			{
				steps
				{
					sh 'mvn clean'
				}
			}
			stage('Build Stage')
			{
				steps
				{
					sh 'mvn install'
				}
			}
			stage('Build Success')
			{
				steps
				{
					echo 'Build Success'
				}
			}	

			stage('Final Success')
			{
				steps
				{
					echo 'Final Success'
				}
			}	
		}
}
