// Declarative //
pipeline {
  agent any
	tools {
		jdk "JAVA_HOME"
		maven "MAVEN_HOME"
	}
  stages {
  	stage('Build') {
	  steps {
	  sh 'mvn clean install'
	  }
  	}
  }
}
// Script //
