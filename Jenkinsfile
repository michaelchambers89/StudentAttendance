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
		sh label: '', script: 'javac -cp  junit-4.13.jar:. Student.java studentTest.java'
            }
        }
        stage('Test') {
            steps {
		sh label: '', script: 'java -cp junit-4.13.jar:hamcrest-core-1.3.jar:. org.junit.runner.JUnitCore studentTest'
            }
        }
    }
}
