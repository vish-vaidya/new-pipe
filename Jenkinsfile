pipeline {
agent {

node {
			label 'master'
			customWorkspace '/mnt/new-'

}

}

stages {

	stage ('clean'){
	
		steps {
				sh "mvn test"
		}
	
	}

	stage ('installing'){
	
		steps {
				sh "mvn install"
                       
		}
	
	}
}
}
