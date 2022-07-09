pipeline {
  agent any
  stages {
    stage('Ejecucion jobs') {
      steps {
        sh '''cd C:\\ 
D:
cd D:\\Alejandro carpetas\\Alejandro\\Universidad\\Semestre 7 - Ing.Informatica\\Pruebas y gestion de la configuracion\\Tarea jenkins

if not exist CarpetaPrueba\\ (md CarpetaPrueba && echo Carpeta creada correctamente) else (echo Ya existe la carpeta)

'''
        sh '''cd C:\\
D:
cd D:\\Alejandro carpetas\\Alejandro\\Universidad\\Semestre 7 - Ing.Informatica\\Pruebas y gestion de la configuracion\\Tarea jenkins\\CarpetaPrueba

if not exist Archivoprueba.txt (echo Fecha:%Date%  Hora:%time% > ArchivoPrueba.txt && echo Archivo creado correctamente) else (echo Ya existe el Archivo)
'''
        sh '''cd C:\\
D:
cd D:\\Alejandro carpetas\\Alejandro\\Universidad\\Semestre 7 - Ing.Informatica\\Pruebas y gestion de la configuracion\\Tarea jenkins\\CarpetaPrueba
if exist Archivoprueba.txt (Move "ArchivoPrueba.txt" "D:\\Alejandro carpetas\\Alejandro\\Universidad\\Semestre 7 - Ing.Informatica\\Pruebas y gestion de la configuracion\\Tarea jenkins" && echo Archivo Movido correctamente) else (echo EL Archivo no existe o ya se movio)'''
      }
    }

  }
}