pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'npm install' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy Java application") { 
         steps { 
           sh 'echo "deploying Java application..."'
         }

     }
  
   	}

   }
