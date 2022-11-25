@Library('jenkins-shared-library-groovy-practice') _

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
