# Karate training by Elvis Mieles

Se realizar la automatización de las APIs https://qa-react-conduit.herokuapp.com/api

Comenzando ✒️

Con este proyecto se desea realizar una automatización de Backend basandonos en los principios SOLID y FIRST, para un mejor entendimiento en los resportes se utiliza BDD,  y serenity con el gestor de dependencias Maven.

Pre-requisitos 📋

Para la ejecución de este proyecto desdemos tener presente que debemos tener instalado el JDK de java y las variables de entorno, las cuales son:

JAVA_HOME: Descarga el JDK de Java y adjuntamos la ruta en donde se encuentra la carpeta, en mi caso la tengo en C:\Program Files (x86)\Java\jdk1.8.0_251

MAVEN_HOME: Descarga el Apache Maven y se adjunta la ruta en donde se encuentre la carpeta, en mi caso la tengo en C:\Program Files\apache-maven-3.6.3-bin\apache-maven-3.6.3
Tener un IDE instalado para la observación o modificación del codigo.

Ejecutando las pruebas ⚙️

Para la ejecución del proyecto debe tener presente que las variables de entornos se encuentre bien configuradas, adicional debe tener las dependencias descargadas la cual se encuentra en el archivo pom.xml.

La prueba se puede ejecutar por medio del package runners, la cual esta ubicada en src/test/java/karate  o por medio de la consola del proyecto con el comando

mvn -Dtest=nombreDeLaClaseRunners “-Dkarate.options=--tags nombreTag” test
   
Reporte 📋

Para observar las evidencias de las pruebas debemos ingresar a la ruta Reporte\site\serenity y buscar archivo Index que se encuentra en la carpeta.



