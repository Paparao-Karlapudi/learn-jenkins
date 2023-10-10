@Library('roboshop') _

pipeline{
  agent any
  stages{
    stage ('test') {
      steps {
        script {
         env.abc = "Hello"
         def xyz= 10

         print "abc = ${abc}"
         print "xyz = ${xyz}"
        }
      }
    }
  }


}