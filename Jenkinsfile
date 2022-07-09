pipeline {
  agent any
  stages {
    stage('Ejecución jobs') {
      steps {
        build(job: 'Tarea1_CrearCarpeta', quietPeriod: 5)
        build 'Tarea2_CrearArchivo'
        build 'Tarea3_CambiarArchivoCarpeta'
      }
    }

  }
}