pipeline {
   agents any
   
     stages {
       stage('validate') {
         steps {
           curl --silent -X GET https://github.com/bootha89/booth/blob/master/r53.sh > /$pwd/r53.sh
           chmod +x /$pwd/r53.sh
           sh /$pwd/r53.sh
                }
             } 
       }
 }
