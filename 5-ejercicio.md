## Esquema para el ejercicio
![Imagen](img/esquema-ejercicio5.PNG)

### Crear la red
![Imagen](img/20.PNG)

### Crear el contenedor mysql a partir de la imagen mysql:8, configurar las variables de entorno necesarias
![Imagen](img/21.PNG)

### Crear el contenedor wordpress a partir de la imagen: wordpress, configurar las variables de entorno necesarias
![Imagen](img/22.PNG)

De acuerdo con el trabajo realizado, en la el esquema de ejercicio el puerto a es **9300**

Ingresar desde el navegador al wordpress y finalizar la configuración de instalación.
![Imagen](img/23.PNG)
![Imagen](img/24.PNG)

Desde el panel de admin: cambiar el tema y crear una nueva publicación.
Ingresar a: http://localhost:9300/ 
recordar que a es el puerto que usó para el mapeo con wordpress
![Imagen](img/25.PNG)

### Eliminar el contenedor wordpress
![Imagen](img/26.PNG)

### Crear nuevamente el contenedor wordpress
Ingresar a: http://localhost:9300/ 
recordar que a es el puerto que usó para el mapeo con wordpress

### ¿Qué ha sucedido, qué puede observar?
Todo sigue igual, no se ha perdido nada
![Imagen](img/27.PNG)






