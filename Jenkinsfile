@Library('jenkins-sharedlibrary') _

pipeline{
	agent any
    stages{
	    stage('Code Scanning'){
		    steps{
			    script{
			    	scan()
			    }
		    }
	    }
        stage('Build'){
            steps{
		    script{
			    build()
		    }
            }
        }
        stage('Deploy'){
            steps{
		    script{
			    deploy()
		    }
            }

        }
    }
}
