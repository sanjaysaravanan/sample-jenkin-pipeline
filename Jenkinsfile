// Declarative //
pipeline {
  agent any
  stages {
	  stage('Build') {
		  steps {
			echo 'Branch Building..'
		  }
	  }
	  stage('Test') {
		  steps {
			echo 'Branch Testing..'
		  }
	  }
	  stage('Deploy') {
		  steps {
			echo 'Branch Deploying....'
		  }
	  }
  }
}
// Script //
node {
  stage('Build') {
	echo 'Branch Building....'
  }
  stage('Test') {
	echo 'Branch Building....'
  }
  stage('Deploy') {
	echo 'Branch Deploying....'
  }
}
