pipeline {
         agent any
         triggers{ 
                  cron('H/15 * * * *') 
                 }
         stages {
                 stage('One') {
                 steps {
                     echo 'Hi, welcome to pipeline demo...'
                 }
                 }
                 stage('Two') {
                 steps {
                    echo('Sample testing of Stage 2')
                 }
                 }
                 stage('Three') {
                
                 steps {
                       echo 'Thanks for using Jenkins Pipeline'
                       }
                 }
                  
              }
}
