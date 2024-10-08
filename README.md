# Información sobre el dataframe netflix_originals:

- Este dataframe contiene información sobre los títulos originales de netflix. Incluye información sobre el título, género, fecha de lanzamiento, duración, notas en IMDB y el idioma.

- Es un data frame con 7 valores de agrupación diferentes y 513 peliculas totales por columna.

- Todos los datos corresponden al sentido común y tienen el tipo adecuado.

- Columna **'Unnamed:0'** eliminada, ya que no aporta al ser un índice redundante. Se ha eliminado a través de indicar que el indice donde comienza el data frame es la posición 0 y no un indice añaido por defecto. Ya que para este caso añade una columna de más.

- No hay valores duplicados generales. Tampoco hay títulos iguales en diferentes idiomas no registrados como tal.

- Los principales géneros de películas son documentales (24,7%), drama (14,2%) y comedias (8,1%). Los menos comunes son animación, comedias sobre danza y animación. Todas con un 1,9% del total.-- (Para un futuro me gustaría implementar un método de separación de géneros para aumentar la precisión).

- No existen datos nulos en la base.

- La media de duración de cada show es de una hora y media (94 minutos).


# Conclusiones generales sobre el dataframe netflix_titles

- En este dataframe hay titulos de peliculas y series de Netflix.

- Existen 13 columnas y 8807 peliculas y series. La mayoria son de tipo objeto. Existen 11 columnas de tipo objeto y 2 int.

- Hay valores nulos pero no duplicados. Las columnas con valores nulos son: director, cast, country, date_added, rating,duration.

- Exiten 6131 peliculas y 2676 series en total.

- En cuanto a las clasificaciones de edad la mayoria de peliculas estan clasificadas con TV-MA. Son 2062 filas que equivale a un 23.42% del total. La clasficación de edad de las series que más porcentaje tiene es TV-MA con un total de 1145 que equivale a un 13.01% del total. Dentro de esta categoría existen datos, en concreto 3 filas, que nos generarán inconsistencias al hacer un análisis en el futuro, estos datos tienen que ver con la duración de las peliculas.

- El director que más peliculas o tv shows es Rajiv Chilaka con 19 pelliculas que equivale a un 0.03% del total.

- En un futuro se podría poner como indice la columna 'show_id'. Resulta ser el identificador de cada serie y son valores unicos.

- El pais con más producciones de peliculas es United States con 2818 que equivale a un 35.33% del total. Pero hay un dato que no concuerda y es que indica de nuevo United States dentro del grupo de paises con solo 1 pelicula producida, esto puede producir inconsistencias en el análisis posterior

- La fecha en la que se añadio la última pelicula fue el 1 de Enero de 2020.