pipeline {
    agent any


    stages 
    {  
        
        stage ('SCM Checkout') {
          git 'https://github.com/rakesh-rupesh/maven-project'
         }
    
    }
    {
                            
        
        stage ('Testing Stage') {


            steps {
                withMaven(maven : 'Local MVN')
                {
                    sh 'mvn test'
                }
                  }
                                 
        }
		}
		}
		
