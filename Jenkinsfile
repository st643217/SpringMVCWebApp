pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                bat 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                bat '''C:\\Program Files (x86)\\Jenkins\\workspace\\SpringWebAppPipeline\\target\\*.war  C:\\Program Files\\Apache Software Foundation\\Tomcat 8.5_Tomcat8.1\\webapps
            }
        }
    }
}