pipeline
{
 agent
 {
     node
     {
         label 'Linux'
     }
 }
 stages
 {
     stage("stage 1")
     {
         steps
         {
            sh '''
                 echo "This is my first pipeline script"
                 echo "This is my first stage"
               '''
         }
     }
     stage ("stage 2")
     {
         steps
         {
             sh '''
                    echo "This is my second stage"
                '''
         }
     }
 }




}
