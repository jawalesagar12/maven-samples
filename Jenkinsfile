pipeline {
		agent any
		tools {
			maven 'Maven 3.6.2'
			jdk 'jdk1.8.0_221'
		}
		stages {
				stage ('Initialize'){
					steps {
						sh '''
							echo "PATH = ${PATH}"
							echo "M2_HOME = ${M2_HOME}"
						'''
					}
				}
			
		}
		stages {
				stage ('Build'){
					steps {
						echo "This is a minimal pipeline."
					}
				}
			
		}
		}