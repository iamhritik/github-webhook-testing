pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                echo "hello world 1"
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
