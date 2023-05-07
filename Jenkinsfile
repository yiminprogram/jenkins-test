pipeline{
    agent any
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