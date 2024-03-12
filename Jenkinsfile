pipeline {
    agent any
    parameters {
     choice choices: ['NIGERIA', 'LIBAN', 'USA'], description: 'CHOOSE YOUR COUNTRY', name: 'COUNTRY'
     string defaultValue: 'SAHAR', description: 'PROVIDE YOUR NAME', name: 'NAME'
     choice choices: ['ECR', 'DOCKERHUB', 'NEXUS'], description: 'CHOOSE YOUR REGISTRY', name: 'REGISTRY'
    }

    stages {




        stage('build') {
            steps {
                echo 'Hello World'
            }
        }


        stage('test') {
            steps {
                echo 'Hello World'
            }
        }



        stage('deploy') {
            steps {
                echo 'Hello World'
            }
        }



        





    }


}
