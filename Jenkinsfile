pipeline{

    agent any

    parameters {
        string defaultValue: '', name: 'version'
    }

    stages{
        stage('first'){
            steps{
                script{
                    def properties = readProperties file : 'gradle.properties'
                    echo "version ${properties.VERSION}"
                }
            }
        }
    }
}