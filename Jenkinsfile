pipeline{

	agent { docker { image 'python:3.5.1' } }
	
	stages{
		stage('Checkout'){
			steps{
				echo 'checking out project'
			}

		}
		
		stage('Build'){
			steps{
				echo 'Building project'
			}
		}

			
		stage('Deploy'){
			steps{
				echo 'Deploying project to environment'
			}
		}
		
		stage('Test'){
			steps{
				echo 'Testing projects with results'
			}
		}
	
	}
}