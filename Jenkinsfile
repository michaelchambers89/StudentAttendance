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
		bat 'mvn clean -f "Users\\user\\ IdeaProjects\\ studentAttendance\\ src\\ studentTest.java"'
            }
        }
        stage('Test') {
            steps {
		cd ..\user\IdeaProjects\studentAttendance\src
		javac studentTest.java
            }
        }
    }
}
