pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
	        sh 'sleep 4'
                echo "Hello World!"
            }
        }

	stage('Test') {
	    steps {
	        sh 'sleep 5'
	        echo "All tests are ok"
	    }
	}

	stage('Deploy') {
	    steps {
	        sh 'sleep 2'
	        echo 'Successfully deployed to staging!'
	    }
	}
    }
}
