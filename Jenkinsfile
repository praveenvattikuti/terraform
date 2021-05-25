pipeline {
  agent any
   options([
    parameters([
        extendedChoice( 
            name: 'PROJECT', 
            defaultValue: '', 
            description: 'Select the DB', 
            type: 'PT_SINGLE_SELECT', 
            groovyScript: valueKeysScript,
            descriptionGroovyScript: valueNamesScript
        )
    ])
])
   stages {
    stage('hello world') {
        steps {
          echo 'hello world'
                  }
}
   }
}