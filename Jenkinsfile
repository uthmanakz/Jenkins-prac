pipeline {
    agent any
    enviroment {
        AWS_ACCESS_KEY_ID = credentials ('AWS_ACCESS_KEY_ID')
        AWS_SECRET_ACCESS_KEY = credentials ('AWS_SECRET_ACCESS_KEY')
    }

    stages {
        stage ( 'list out enviroment' ) {
            steps {
               sh 'env'

         }
        }

        stage ('second stage') {
            steps {
                echo 'this is my second stage'

              


          }
        }
    }

     

}