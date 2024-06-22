pipeline {
    agent 
    {
        label "slave-1"
    }
    

    stages {
        stage ('Compile Stage') {

            steps {
                
                   echo "first stage"
                }
            
        }

        stage ('Testing Stage') {

            steps {
                
                    echo "second stage"
                }
            
        }


        stage ('Install Stage') {
            steps {
                
                     echo "third changes"
                }
            
        }
        
        stage ('Echo Branch') {

            steps {
                
                    echo "This is dev branch"
                }
            
        }
    }
}
