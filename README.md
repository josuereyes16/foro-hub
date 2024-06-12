## API REST Forum / Foro API REST → [josuereyes16](https://github.com/josuereyes16)

| Description | Descripcion |
|---------|---------|
| This project involves developing a REST API for a forum using Java and Spring Boot. The API allows users to create, list, and delete discussion topics. Authentication and authorization are implemented using JWT to ensure that only registered users can perform certain actions. Insomnia is used to test the functionality of the endpoints.| Este proyecto consiste en desarrollar una API REST para un foro utilizando Java y Spring Boot. La API permite a los usuarios crear, listar y eliminar tópicos de discusión. Se implementa autenticación y autorización mediante tokens JWT para asegurar que solo los usuarios registrados puedan realizar ciertas acciones. Las pruebas se realizan con la herramienta Insomnia para verificar la funcionalidad de los endpoints.|

---

| Features | Características |
|---------|---------|
| - Search book by title: Allows searching for books by title in the API and registering them in the database. | - Buscar libro por título: Permite buscar libros por su título en la API y registrarlos en la base de datos.
| - List registered books: Displays all books registered in the database. | - Listar libros registrados: Muestra todos los libros registrados en la base de datos.
| - List registered authors: Displays all authors registered in the database. | - Listar autores registrados: Muestra todos los autores registrados en la base de datos.
| - List living authors in a specific year: Allows filtering authors who were alive in a specific year. | - Listar autores vivos en un año específico: Permite filtrar autores que estaban vivos en un año determinado.
| - List books by language: Classifies registered books by language. | - Listar libros por idioma: Clasifica los libros registrados por idioma.


---

| Installation | Instalación |
|---------|---------|
| Clone the repository: git clone https://github.com/tu_usuario/foro-api-rest.git	|Clonar el repositorio: git clone https://github.com/tu_usuario/foro-api-rest.git|
|Navigate to the project directory: cd foro-api-rest	|Navegue al directorio del proyecto: cd foro-api-rest|
|Create a project in Spring Initializr:	|Crear un proyecto en Spring Initializr:|
|`Visit start.spring.io.` <br> `Select Maven, Java, and the latest version of Spring Boot.` <br> `Add dependencies: Spring Web, Spring Data JPA, and Spring Security.` |	`Visite start.spring.io.` <br> `Seleccione Maven, Java y la última versión de Spring Boot. `<br> `Agregue dependencias: Spring Web, Spring Data JPA y Spring Security.`|
|Import the project into your preferred IDE.|	Importe el proyecto a su IDE preferido.|
|Configure the database in application.properties:	|Configure la base de datos en application.properties:|
|`spring.datasource.url=jdbc:postgresql://localhost:5432/database_name` <br> `spring.datasource.username=username` <br> `spring.datasource.password=password` <br> `spring.jpa.hibernate.ddl-auto=update` | `spring.datasource.url=jdbc:postgresql://localhost:5432/database_name` <br> `spring.datasource.username=nombre de usuario` <br> `spring.datasource.password=contraseña `<br> `spring.jpa.hibernate.ddl-auto=update`|
|Run the application: ./mvnw spring-boot:run|	Ejecute la aplicación: ./mvnw spring-boot:run|

---

| Contribution | Contribuciones |
|---------|---------|
| Fork the repository.|Bifurca el repositorio.|
|Create a new branch: `git checkout -b feature/new-feature`	|Crea una nueva rama: `git checkout -b feature/new-feature`|
|Make changes and commit them: `git commit -m "Add new feature"`|	Realice cambios y confírmelos: `git commit -m "Agregar nueva característica"`|
|Push the changes to the remote repository: `git push origin feature/new-feature`	|Envía los cambios al repositorio remoto: `git push origin feature/new-feature`|
|Create a Pull Request on GitHub.	|Crea una solicitud de extracción en GitHub. |

----

| Usage | Uso |
|---------|---------|
| List all topics in the forum.|	Lista todos los tópicos en el foro.|
|Create new topics after authenticating with JWT.	|Crea nuevos tópicos después de autenticarse con JWT.|
|Delete existing topics after authenticating with JWT.|	Elimina tópicos existentes después de autenticarse con JWT.|
|Authenticate users to ensure secure access to endpoints. | Autentica usuarios para asegurar acceso seguro a los endpoints.|
