pipeline {
agent {

node {
			label 'master'
			customWorkspace '/mnt/project/game-of-life'

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
