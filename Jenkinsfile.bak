def CCS2_AUTOSAR_DOWNLOAD(){
   bat """
      python C:\\Users\\MGT3KOR\\.jenkins\\workspace\\Scripted_pipeline\\PY_SPT\\PRINT.py
   """
}
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
