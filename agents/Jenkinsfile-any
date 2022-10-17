pipeline {
    agent any
    stages {
        stage('BUILD') {
          steps {
             sh '''
                 #!/bin/bash
                 pwd
                 ls
                 echo "this is build stage"
           '''  
          }
        }
    stage('DEPLOY') {
          steps {
             echo 'this is deploy stage'
             sh 'echo bla'
             sh '''echo "gfhgf vjg jhfjhf"'''
          }  
        }
    stage('TEST1') {
          steps {
             sh 'echo "this is test1 stage"'
          }  
        }
    stage('TEST2') {
          steps {
             sh '''
             echo "1234 sdfgh fghj 789" 
            '''
          } 
        }
    }
}
