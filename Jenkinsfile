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
		cd ..\user\IdeaProjects\studentAttendance\src\javac Student.java
		
            }
        }
        stage('Test') {
            steps {
		cd ..\user\IdeaProjects\studentAttendance\tests\javac studentTest.java
		
            }
        }
    }
}
