// Declarative //
pipeline {
  agent any
	tools {
		jdk "JAVA_HOME"
		maven "MAVEN_HOME"
	}
  stages {
  	stage('Test') {
	  steps {
	  sh 'mvn -version'
	  }
  	}
  }
}
// Script //
