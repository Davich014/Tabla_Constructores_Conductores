Tabla_Constructores_Conductores

Este código crea una aplicación JavaFX que se conecta a una base de datos MySQL, obtiene los datos de los constructores de Fórmula 1 y los muestra en una tabla interactiva.

1.- Importaciones: Se importan las clases necesarias de JavaFX y Java.sql para trabajar con la interfaz gráfica y la conexión a la base de datos.

2.- Clase Resultconstructor: Esta clase extiende de la clase Application de JavaFX, lo que significa que es la clase principal de la aplicación.

3.- Método start(): Este método es el punto de entrada de la aplicación y se ejecuta cuando se inicia la aplicación.

4.- Crear la tabla: Se crea una instancia de TableView que será la tabla donde se mostrarán los datos.

5.- Crear las columnas: Se crean las columnas de la tabla, cada una con un título y una propiedad correspondiente de la clase datos.

6.- Conectar a la base de datos: Se establece una conexión a la base de datos MySQL utilizando las credenciales proporcionadas (url, usuario y contraseña).

7.- Obtener los datos de la base de datos: Se ejecuta una consulta SQL para obtener todos los registros de la tabla constructors y se crea una lista observable de objetos datos con los datos obtenidos.

8.- Asignar los datos a la tabla: Se asigna la lista de constructores a la TableView para que se muestren en la tabla.

9.- Crear la escena y mostrar la tabla: Se crea una BorderPane como raíz de la escena y se coloca la TableView en el centro. Finalmente, se crea la escena, se establece en el Stage principal y se muestra la aplicación.

10.-  Método main(): Este método es el punto de entrada de la aplicación y llama al método launch() para iniciar la ejecución de la aplicación.
