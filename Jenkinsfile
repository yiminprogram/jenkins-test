def properties = readProperties file : 'gradle.properties'
pipeline{

    agent any

    parameters {
        string defaultValue: "${properties.VERSION}", name: 'apple'
    }

    stages{
        stage('first'){
            steps{
                script{
                    echo "version ${params.apple}"
                }
            }
        }
    }
}