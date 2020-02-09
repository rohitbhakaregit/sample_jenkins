pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
            echo "build number => ${env.BUILD_NUMBER}"  >> /tmp/tmp.txt
         }
      }
      stage('execute shell script') {
         steps {
            echo 'I am executing the scrip'
            sh label: '', script: 'echo "hi from the pipeline" >> /tmp/tmp.txt'         }
      }
     
   }
}
