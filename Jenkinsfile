pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
            git 'https://github.com/devopstraining042024/hello-world1.git'

        }
     }
     
     stage('Test') { 
        steps { 
           bat 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           bat 'echo "deploying application..."'
         }

     }
  
   	}

   }
