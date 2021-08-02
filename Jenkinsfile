pipeline {
    agent any
    stages {
       
        stage('Send email') {
            

            steps {
                script {
                    def datas = readYaml file: 'values.yaml'
                    echo "Got version as ${datas.injector.replicas}"

                }
            }
                
        }
    }

}
