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

    }
}
