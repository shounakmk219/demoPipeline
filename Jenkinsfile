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

               

                bat 'mvn deploy'

            }

        }

    }

}
