pipeline {
	
		agent any
		tools {
			maven 'Maven 3.6.2'
			jdk 'jdk1.8.0_221'
		}
		stages {
				stage ('Build'){
					steps {
						bat 'mvn -Dmaven.test.failure.ignore=true install' 
						}
					post {
						success {
						echo "Build is successful" 
						}
					}
				}
				stage ('Packaging'){
					steps {
						bat 'mvn -Dmaven.test.failure.ignore=true install' 
						}
		}
		}
}
