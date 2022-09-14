pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                echo "hello world"
            }
        }
		stage ('Deployment') {
			steps {
				echo "deployment stage"
			}
		}
		stage ('Environment check') {
			steps {
				echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"
			}
		}
    }
}
