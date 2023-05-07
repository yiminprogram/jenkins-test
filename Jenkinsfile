node{
    def prop = readProperties file : 'gradle.properties'
    properties([
  parameters([
    string(name: 'apple', defaultValue: "${prop.VERSION}"),
  ])
])
    stage('Node'){
        echo "Hello ${params.apple}"
    }
}