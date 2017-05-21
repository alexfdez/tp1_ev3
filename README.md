# Pasos a seguir para usar este proyecto:

### 1. Clonamos el proyecto:

            $git clone https://github.com/alexfdez/tp1_ev3.git

### 2. Nos situamos en la carpeta correspondiente del proyecto:
            cd tp1_ev3
 
### 3. Compilamos el JunitTestSuite del proyecto y especificamos la ruta en la que se encuentra el .jar de Junit:

            $ javac -cp ~/misjars/junit/*:. JunitTestSuite.java
      
### 4. Tras compilar, comprobamos si los test se ejecutan sin problema:

            $ java -cp ~/misjars/junit/*:. org.junit.runner.JunitCore JunitTestSuite
            
### El resultado tras el anterior comando, si no se han encontrado errores deberá mostrar en la consola:

            OK (5 tests)
