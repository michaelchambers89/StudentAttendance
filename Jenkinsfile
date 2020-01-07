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
		sh 'javac Student.java studentTest.java'
            }
        }
        stage('Test') {
            steps {
		sh '''
                java -cp junit-4.13.jar;hamcrest-core-1.3.jar;. org.junit.runner.JUnitCore studentTest
                '''
            }
        }
    }
}
