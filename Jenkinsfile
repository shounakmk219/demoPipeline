pipeline {

    agent any    

    stages {

        stage ('Compile Stage') {



            steps {

              

                 bat 'mvn clean install'

            }

        }


        stage ('Deployment Stage') {



            steps {







                bat 'java -jar target/demoPipeline-0.0.1-SNAPSHOT.jar'



            }



        }
       

    }

}
