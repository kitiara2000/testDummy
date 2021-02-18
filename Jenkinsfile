pipeline {
   agent { label 'master' }
   stages {
       stage('read') {
           steps {
               script {
                   println(file: 'DummySample.txt')
               }
           }
       }
   }
}
