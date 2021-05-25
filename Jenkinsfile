pipeline {
    agent any
    stages {
        stage('Example') {
            input {
                message "Select the DB"
                ok 'Proceed!'
                parameters {
                    extendedChoice defaultValue: 'blue,green,yellow,blue', description: '', descriptionPropertyValue: 'blue,green,yellow,blue', multiSelectDelimiter: ',', name: 'DB_Name', quoteValue: false, saveJSONParameterToFile: false, type: 'PT_MULTI_SELECT', value: 'blue,green,yellow,blue', visibleItemCount: 5
                }
            }
            steps {
                echo "Your favorite color is ${favColor}"
            }
        }
    }
}