pipeline {
   agent { label 'master' }
   stages {
       stage('read') {
           steps {
               script {
                   def data = readFile(file: 'DummySample.txt')
                   println(data)
               }
           }
       }
   }
}
