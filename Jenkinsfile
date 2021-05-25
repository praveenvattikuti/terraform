pipeline {
    agent any
    stages {
        stage('Example') {
            input {
                message "Select the DB"
                ok 'Proceed!'
                parameters {
                    extendedChoice defaultValue: 'test_db1,test_db2,test_db3,test_db4', description: '', descriptionPropertyValue: 'test_db1,test_db2,test_db3,test_db4', multiSelectDelimiter: ',', name: 'DB_Name', quoteValue: false, saveJSONParameterToFile: false, type: 'PT_MULTI_SELECT', value: 'test_db1,test_db2,test_db3,test_db4', visibleItemCount: 5
                }
            }
            steps {
                echo "Your favorite color is ${DB_Name}"
            }
        }
    }
}