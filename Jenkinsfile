pipeline {
    agent any

    stages {
        
        stage ('Testing Stage') {

            steps {
               // withMaven(maven : 'maven3.5.0') {
                    
		    bat  'mvn test'
               // }
            }
        }


        stage ('Install Stage') {
            steps {
              //  withMaven(maven : 'maven3.5.0') {
                    bat 'mvn install'
               // }
            }
        }
    }
}
