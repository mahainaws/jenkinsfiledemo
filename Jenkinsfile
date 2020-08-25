pipeline {
    agent any
// testing the jenkins ***************
    stages {
        stage ('Compile Stage') {

            steps {
                //withMaven(maven : 'maven3.3.9') {
		    bat 'mvn -version'
                    bat 'mvn clean compile'
            //   }

			  
			  // Added new comment
		    // added new line
			}
        }

        stage ('Testing Stage') {

            steps {
               // withMaven(maven : 'maven3.3.9') {
                    
		    bat  'mvn test'
               // }
            }
        }


        stage ('Deployment Stage') {
            steps {
              //  withMaven(maven : 'maven3.3.9') {
                    bat 'mvn install'
               // }
            }
        }
    }
}
