pipeline { 
  
   agent any

   stages {
   
     stage('Cloning Git') { 
        steps { 
           sh 'npm install'
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
