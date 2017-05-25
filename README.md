# TP1 3 Ev. 

# 1. Clonar el proyecto

      $ git clone https://github.com/alexfdez/tp1_ev3.git
      
# 2. Nos situamos en el directorio del proyecto
           
      $ cd tp1_ev3
      
# 3. Ejecutamos maven para ejecutar los test
      
      $ mvn test
  
# Comprobamos que se ha realizado sin ningun error y observamos que nos muestra:

      [INFO] Scanning for projects...
      [INFO]                                                                         
      [INFO] ------------------------------------------------------------------------
      [INFO] Building tp1_maven 0.0.1-SNAPSHOT
      [INFO] ------------------------------------------------------------------------
      [INFO]
      [INFO] --- maven-resources-plugin:2.6:resources (default-resources) @ TrabajoPractico_2 ---
      [INFO] Using 'UTF-8' encoding to copy filtered resources.
      [INFO] skip non existing resourceDirectory /home/freddiew/Escritorio/tp1_ev3/src/main/resources
      [INFO]
      [INFO] --- maven-compiler-plugin:3.2:compile (default-compile) @ TrabajoPractico_2 ---
      [INFO] Nothing to compile - all classes are up to date
      [INFO]
      [INFO] --- maven-resources-plugin:2.6:testResources (default-testResources) @ TrabajoPractico_2 ---
      [INFO] Using 'UTF-8' encoding to copy filtered resources.
      [INFO] skip non existing resourceDirectory /home/freddiew/Escritorio/tp1_ev3/src/test/resources
      [INFO]
      [INFO] --- maven-compiler-plugin:3.2:testCompile (default-testCompile) @ TrabajoPractico_2 ---
      [INFO] Nothing to compile - all classes are up to date
      [INFO]
      [INFO] --- maven-surefire-plugin:2.17:test (default-test) @ TrabajoPractico_2 ---
      [INFO] Surefire report directory: /home/freddiew/Escritorio/tp1_ev3/target/surefire-reports

      -------------------------------------------------------
      T E S T S
      -------------------------------------------------------
      Running tp1_ev3.TestPerson
      Tests run: 1, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.468 sec - in Tp2_Ev3.TestPerson
      Running tp1_ev3.MathTest
      Tests run: 4, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.009 sec - in Tp2_Ev3.MathTest
      Running tp1_ev3.AppTest
      Tests run: 1, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.001 sec - in Tp2_Ev3.AppTest

      Results :

      Tests run: 6, Failures: 0, Errors: 0, Skipped: 0

      [INFO] ------------------------------------------------------------------------
      [INFO] BUILD SUCCESS
      [INFO] ------------------------------------------------------------------------
      [INFO] Total time: 12.637 s
      [INFO] Finished at: 2017-05-17T20:08:07+02:00
      [INFO] Final Memory: 8M/20M
      [INFO] ------------------------------------------------------------------------
