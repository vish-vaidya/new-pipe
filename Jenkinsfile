pipeline {
agent {

node {
			label 'node1'
			customWorkspace '/mnt/new-

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
