pipeline
{

	agent any
	stages {
	stage('Fetch') {
			 steps {
                echo "fetch data from orgin"
            }
        }
        stage('Build') {
            steps {
		sh 'javac Student.java'
            }
        }
        stage('Test') {
            steps {
		sh 'javac studentTest.java'
            }
        }
    }
}
