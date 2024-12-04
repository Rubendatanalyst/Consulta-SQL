# Consulta-SQL
SQL

__Contexto__

El coronavirus tomó al mundo entero por sorpresa, cambiando la rutina diaria de todos y todas. Los habitantes de las ciudades ya no pasaban su tiempo libre fuera, yendo a cafés y centros comerciales; sino que más gente se quedaba en casa, leyendo libros. Eso atrajo la atención de las startups (empresas emergentes) que se apresuraron a desarrollar nuevas aplicaciones para los amantes de los libros.
Con la base de datos de uno de los servicios que compiten en este mercado, la cual contiene datos sobre libros, editoriales, autores, calificaciones de clientes y reseñas de libros, se utilizará para generar una propuesta de valor para un nuevo producto.

El objetivo del siguiente proyecto es generar una propuesta de valor sólida para un nuevo producto o servicio dentro del mercado de libros digitales, aprovechando las tendencias y oportunidades surgidas a raíz de la pandemia de COVID-19.

__Descripción de los datos de las tablas__

-books: Contiene datos sobre libros:

•	_book_id_ — identificación del libro.

•	_author_id_ — identificación del autor o autora.

•	_title_ — título.

•	_num_pages_ — número de páginas.

•	_publication_date_ — fecha de la publicación.

•	_publisher_id_ — identificación de la editorial.

-authors: Contiene datos sobre autores:

•	_author_id_ — identificación del autor o autora.

•	_author_ — el autor o la autora.

-publishers: Contiene datos sobre editoriales:

•	_publisher_id_ — identificación de la editorial.

•	_publisher_ — la editorial.

-ratings: Contiene datos sobre las calificaciones de usuarios:

•	_rating_id_ — identificación de la calificación.

•	_book_id_ — identificación del libro.

•	_username_ — el nombre del usuario que revisó el libro.

•	_rating_ — calificación.

-reviews: Contiene datos sobre las reseñas de los y las clientes:

•	_review_id_ — identificación de la reseña.

•	_book_id_ — identificación del libro.

•	_username_ — el nombre del usuario que revisó el libro.

•	_text_ — el texto de la reseña.


__Tabla de Contenido__

En el archivo __'consultas.ipynb'__ se encuentra el siguiente desarrollo de consultas:

- Carga de librerías.
- Conexión a la base de datos.
- Consulta de las tablas.
- Número de libros publicados después del 1 de enero de 2000.
- Número de reseñas de usuarios y la calificación promedio para cada libro.
- Editorial que ha publicado el mayor número de libros con más de 50 páginas.
- Autor que tiene la más alta calificación promedio del libro: libros con al menos 50 calificaciones.
- Número promedio de reseñas de texto entre los usuarios que calificaron más de 50 libros.


