pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
            
            sh label: '', script: 'echo "build number => "  >> /tmp/tmp.txt'       }

         }
     
      stage('execute shell script') {
         steps {
            echo 'I am executing the scrip'
            sh label: '', script: 'echo "hi from the pipeline" >> /tmp/tmp.txt'         }
      }
     
   }
}
