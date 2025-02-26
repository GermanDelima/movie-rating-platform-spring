## Movie Rating Platform (Similar to IMDb)

**Plataforma para puntuar películas**  
Bienvenido a una plataforma de puntuación de películas similar a **IMDb**, donde los usuarios pueden votar y calificar sus películas favoritas. Esta aplicación permite a los usuarios ver, agregar, actualizar y eliminar películas, así como votar por ellas, con el objetivo de mejorar la experiencia de búsqueda y clasificación de películas.

### Características principales:
- **Visualización de películas:** Accede a una lista de películas con sus detalles.
- **Puntuación y votación:** Vota por tus películas favoritas y consulta su calificación actualizada.
- **CRUD de películas:** Agrega, actualiza y elimina películas fácilmente desde la API.
- **Calificación promedio:** La calificación de cada película se calcula dinámicamente, considerando los votos de los usuarios.

### Tecnologías:
- **Backend:** Java con Spring Boot
- **Base de datos:** MySQL
- **API RESTful:** Endpoints para realizar operaciones CRUD y votación
- **Documentación:** Incluye ejemplos de pruebas de la API con Postman.

### Endpoints principales:
- **GET /movies:** Obtén una lista de todas las películas.
- **GET /movies/{id}:** Obtén los detalles de una película por ID.
- **POST /movies:** Crea una nueva película en la base de datos.
- **PUT /movies/{id}:** Actualiza los detalles de una película existente.
- **DELETE /movies/{id}:** Elimina una película de la base de datos.
- **GET /vote/{id}/{rating}:** Vota por una película y actualiza su calificación.



## Pruebas de la API

Aquí tienes ejemplos de las interacciones con la API REST.

### Obtener todas las películas
![GET /movies](https://raw.githubusercontent.com/GermanDelima/movie-rating-platform-spring/refs/heads/main/src/screenshots/GET_movies_list_response.png)

### Crear una nueva película
![POST /movies](https://raw.githubusercontent.com/GermanDelima/movie-rating-platform-spring/refs/heads/main/src/screenshots/POST_create_movie_request.png)


### Actualizar una película existente
![PUT /movies/{id}](https://raw.githubusercontent.com/GermanDelima/movie-rating-platform-spring/refs/heads/main/src/screenshots/PUT_update_movie_request.png)


### Votar por una película
![GET /vote/{id}/{rating}](https://raw.githubusercontent.com/GermanDelima/movie-rating-platform-spring/refs/heads/main/src/screenshots/GET_vote_movie_request.png)


### Eliminar una película
![DELETE /movies/{id}](screenshots/DELETE_delete_movie_request.png)


### ¿Cómo empezar?

1. **Clona el repositorio:**

   ```bash
   git clone https://github.com/tu-usuario/movie-rating-platform.git

2. **Instala las dependencias:**

   ```bash
   mvn install
3. **Configura tu base de datos MySQL con las credenciales adecuadas en**
      ```bash
   application.properties

5. **Ejecuta el proyecto:**
   ```bash
   mvn spring-boot:run

## 📩 Contacto

😊 Si tienes dudas podés hacerlo a través de: **[LinkedIn](https://www.linkedin.com/in/jos%C3%ADasgerm%C3%A1ndelima/)**
