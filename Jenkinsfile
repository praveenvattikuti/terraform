pipeline {
    agent any
    stages {
       
        stage('Send email') {
            

            steps {
                script {
                    def datas = readYaml file: 'values.yml'
                    echo "Got version as ${datas.injector.replicas}"

                }
            }
                
        }
    }

}
