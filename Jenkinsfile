pipeline {
  agent any
   properties([
    parameters([
        extendedChoice( 
            name: 'PROJECT', 
            defaultValue: '', 
            description: 'Sélectionnez le projet à construire.', 
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