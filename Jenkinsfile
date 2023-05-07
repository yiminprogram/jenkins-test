pipeline{
    agent any
    stages{
        stage('first'){
            steps{
                def properties = readProperties file : 'gradle.properties'
                echo "version ${properties.VERSION}"
            }
        }
    }
}