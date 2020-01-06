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
		cd ..\user\IdeaProjects\studentAttendance\src
		bash 'javac studentTest.java'
            }
        }
        stage('Test') {
            steps {
		cd ..\user\IdeaProjects\studentAttendance\src
		bash 'javac studentTest.java'
            }
        }
    }
}
