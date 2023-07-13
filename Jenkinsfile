pipeline{ 
         agent { label "Python" }
		 stages {
		    stage("checkout code") {
		      steps {
		       git 'https://github.com/cricketgit/war-demo-app.git'
		           }
            }
		    stage("build code") {
		     steps {
		         sh "mvn package" 
		         }
            }  
		 }
        }
