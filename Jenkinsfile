pipeline{
	agent any
	
	stages {
		stage('Checkout'){
			steps {
					echo "Checked out Successfully !!" ;
			}
		}
		stage('Compile'){
			steps{
					echo "Junit Passed Successfully !!";
			}
		}
		stage ('Deploy'){ 
			steps {
					echo "App Deployed Successfully !!";
			}
		}
	}
	post {
		always {
			echo "This is a block that will run always !!"
		}
		success {
			echo "This will run only if successful !!"
		}
		failure {
			echo 'This block will run only if failed'
		}
		
	}
} 
