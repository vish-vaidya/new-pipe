pipeline {
agent {

node {
			label 'node1'
			customWorkspace '/mnt/new-'

}

}

stages {

	stage ('clean'){
	
		steps {
				sh "sudo yum install httpd -y"
		}
	
	}

	stage ('installing'){
	
		steps {
				sh "service httpd on"
                       
		}
	
	}
	
	
		stage ('deply'){
	
		steps {
			        sh "chmod -R 777 /var/www/html/"
				sh "cp -r /mnt/index.html /var/www/html/"
                       
		}
	
	}
}
}
