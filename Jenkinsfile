pipeline{

	agent any

	

	stages {

        stage('Clean') {

			steps {
				sh 'mvn clean '
			}
		}

        stage('Install') {

			steps {
				sh 'mvn install '
			}
		}

		stage('Application') {

			steps {
				sh 'mvn spring-boot:run'
			}
		}

	}

}