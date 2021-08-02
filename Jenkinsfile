pipeline {
    agent any
    stages {
       
        stage('Send email') {
            

            steps {
                script {

                     println('Hello World')
                    def datas = readYaml file: 'values.yml'
                    echo "Got version as ${datas.injector.replicas}"

                }
            }
                
        }
    }

}
