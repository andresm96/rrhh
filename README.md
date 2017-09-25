# UTN FRRO - Asignatura: Dise�o de Sistemas.
## RRHH
Aplicaci�n de ejemplo con Spring para agendar entrevistas con candidatos seg�n los conocimientos requeridos.
- Link para ver la aplicaci�n online: [https://utn-frro-ds-rrhh.herokuapp.com/](https://utn-frro-ds-rrhh.herokuapp.com/)

## Software necesario para correr el proyecto
- Descargar e instalar [Java development kit 1.8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) o posterior.
- Descargar e instalar la �ltima versi�n de [Eclipse](https://www.eclipse.org/downloads/) IDE para Java.

## Importar el proyecto en Eclipse
Para importa el proyecto en Eclipse se deben seguir los siguientes pasos:
1. Ir **Men� File > Import > Git > Projects from Git**.
2. Seleccionar **"Clone URI"** e ingresar los siguientes datos:
   - URI: [https://github.com/ignaciopaz/rrhh](https://github.com/ignaciopaz/rrhh)
   - HOST: github.com
   - Repository Path: /ignaciopaz/rrhh
3. Clic en Next.
4. Seleccionar **"Import Existing Eclipse Project"**.
5. Clic en Next.
6. Clic en Finish.

## Descargar dependencias
Antes de ejecutar el proyecto por primera vez se deben descargar las dependencias a trav�s de Maven:
1. Ir al archivo **pom.xml**
2. Hacer clic derecho sobre el mismo y ejecutar **Run as > Maven Clean** 
3. Volver a hacer clic derecho sobre el pom.xml y ejecutar **Run as > Maven Install**.

## Correr la aplicaci�n
Para ejecutar la aplicaci�n:
1. Ir al Paquete edu.utn.frro.ds.reverseengineering.rrhh.
2. Clic derecho en **Application.java** y hacer **Run as Java Application**.
3. Abrir el browser en [http://localhost:8080/](http://localhost:8080/)

## Como ver la base de datos H2
Para ver la consola de la base de datos [H2](http://www.h2database.com/) de la aplicaci�n:
1. En el brower ir a: [http://localhost:8080/h2-console](http://localhost:8080/h2-console)
2. En **"JDBC URL"** ingresar: **jdbc:h2:mem:testdb**
3. Clic en **"Connect"**
