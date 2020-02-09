pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
            echo 'Hello World'
         }
      }
      stage('execute shell script') {
         steps {
            echo 'I am executing the scrip'
            sh label: '', script: 'echo "hi from the pipeline" >> /tmp/tmp.txt'         }
      }
     
   }
}
