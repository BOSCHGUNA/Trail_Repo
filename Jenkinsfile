def CCS2_AUTOSAR_DOWNLOAD(){
   bat """
      python C:\\Users\\MGT3KOR\\.jenkins\\workspace\\Scripted_pipeline\\PY_SPT\\PRINT.py ${RELEASE_LABEL}
   """
}
properties([
    parameters([
        string(name: 'RELEASE_LABEL', defaultValue: 'ccs2', description: 'The name of the build version', trim: true),

        ])
    ])

pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                script{
                    CCS2_AUTOSAR_DOWNLOAD()
                }
            }
        }
    }
}
