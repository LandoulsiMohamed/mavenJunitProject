
pipeline {
  
          agent any

          stages{
            stage('Get from git project'){
  steps {
    git 'https://github.com/LandoulsiMohamed/mavenJunitProject'
  }
            }

           // Create a new .jar file 

            stage('Create a new .jar') {

                steps {
                    
                  // sh 'mvn clean install -DskipTests'
                  echo "success"
                
                      }

          
            }
}
}
