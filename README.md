# UTN FRRO - Asignatura: Dise�o de Sistemas.
# RRHH
Aplicaci�n de ejemplo con Spring para agendar entrevistas con candidatos seg�n los conocimientos requeridos.
- Link para ver la aplicaci�n online: [https://utn-frro-ds-rrhh.herokuapp.com/](https://utn-frro-ds-rrhh.herokuapp.com/)

## Imporar el proyecto en Eclipse
- Ir Men� File>Import>Git>Projects from Git
  - Clone URI
	- URI: https://github.com/ignaciopaz/rrhh
	- HOST: github.com
2. Repository Path: /ignaciopaz/rrhh
Next
Import Existing Eclipse Project
Next
Finish

Para ejecutar 
Ir a Paquete edu.utn.frro.ds.reverseengineering.rrhh
Clic derecho en Application.java y hacer Run as Java Application

Ver base de datos H2:
En el brower ir a: http://localhost:8080/h2-console
JDBC URL: jdbc:h2:mem:testdb
Connect
