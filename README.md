# Despliegue-docker  
Tendremos que tener un archivo YAML como la siguiente imagen donde la clave es **root** y el usuario es **testuser**.
![image](https://user-images.githubusercontent.com/91737963/173252339-3bb16ba2-1162-4ca0-a392-5ca579e7ca21.png)  
Acto seguido lanzamos el comando <code>docker-compose up -d</code>
![image](https://user-images.githubusercontent.com/91737963/173250724-3335f36c-1c82-4266-bdbd-c44315e0a2b9.png)  
Una vez que haya arrancado todo los contenedores. Utilizamos el siguiente cmd <code>docker ps</code> para ver que esta todo en funcionamiento.  
![image](https://user-images.githubusercontent.com/91737963/173250748-e5dabcac-db9b-4652-b83a-8b0282c9d5e4.png)  
Acontinuación para acceder al phpMyAdmin tendremos que acceder con 'localhost:8081'  
![image](https://user-images.githubusercontent.com/91737963/173251239-7c4cb39f-b751-4cb7-a5a7-3ba109a585fb.png)  
Como mencione anteriormente Username: **testuser** y Password: **root**
![image](https://user-images.githubusercontent.com/91737963/173251936-b29b56d8-58ea-47e1-93a7-cdb0cac11a3c.png)  
Acontinuación se puede ver que podimos acceder al phpMyAdmin:  
![image](https://user-images.githubusercontent.com/91737963/173252075-d3a6698c-9ccc-4259-a92d-b16b867ee855.png)  
Con 'localhost:8082/LoginWebApp' nos lleva a la parte de Login:  
![image](https://user-images.githubusercontent.com/91737963/173251629-84b39fe2-5a04-4cd3-bc13-ca00a4a301c4.png)  
Acontinuación se puede ver que pulsando el boton **Register Here** en la imagen anterior nos llevara a la zona de registro donde introduciremos nuestros datos y le daremos **Submit** una vez que ya este todo completado  
![image](https://user-images.githubusercontent.com/91737963/173251660-e5208301-7adf-41a4-af99-426aa1b2156a.png)


