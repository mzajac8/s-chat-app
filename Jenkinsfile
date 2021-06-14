pipeline{
	agent any
	tools {nodejs "nodejs"}
	stages{
		stage('Testng'){
			steps {
				echo 'Testing'
				sh 'npm test'
			}
		}
	}
}
