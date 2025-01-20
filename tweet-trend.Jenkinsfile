pipeline {

    agent {

        node {

            label 'mvn'

        }

    }
environment{
    PATH="/opt/apache-maven-3.9.9/bin:$PATH"
}

 

    stages {

        stage('Build') {

            steps {

                sh "mvn clean deploy"

            }

        }

    }

}
