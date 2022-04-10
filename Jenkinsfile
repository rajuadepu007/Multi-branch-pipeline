pipeline { 
  
   agent any

   stages {
   
     stage('Cloning Git') { 
        steps { 
           git branch: 'main', url: 'https://github.com/rajuadepu007/Multi-branch-pipeline-node-js.git'
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
