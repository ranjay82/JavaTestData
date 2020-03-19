pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                 bat 'mvn clean'
                // withMaven(maven : 'maven_3_6_3') {
                //     sh 'mvn clean compile'
                // }
            }
        }

        // stage ('Testing Stage') {

        //     steps {
        //         sh 'mvn test'
        //         // withMaven(maven : 'maven_3_6_3') {
        //         //     sh 'mvn test'
        //         // }
        //     }
        // }


        // stage ('Deployment Stage') {
        //     steps {
        //          sh 'mvn deploy'
        //         // withMaven(maven : 'maven_3_6_3') {
        //         //     sh 'mvn deploy'
        //         // }
        //     }
        // }
    }
}