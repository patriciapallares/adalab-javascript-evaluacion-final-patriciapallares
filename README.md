# Evaluación final módulo 2 Patricia Pallarés González

Notas presentación enunciado:
ASWK opcional

Buscador por nombre de bebidas del mundo.
-Cuando carga la página no hay nada.
-Pinta un listado de resultados
Se pueden añadir o no a fav

Api proporcionada por los profes. Enlace a la documentación. 

Algunos cócteles no tienen imagen. 
-opción 1. generador de imagen drink
-opción 2. diseñar una imagen default 

Podemos usar innerHTML o DOM avanzado

PINTAR la lista de cócteles favoritos y lista general

Añadir estilos para diferenciar que ya está contenido en favoritos

Almacenamiento local 

Reset borrar favoritos, lista, y SL
BONUS borrar de favoritos y quitar estilo diferenciador
BONUS2 añadir estilos D:

Normas:

max 11/04 a las 14
github pages 


Interpretación del enunciado:

Queremos una aplicación web que contenga un listado de bebidas internacionales, que permita a la user des/marcar sus favoritas y que se guarde en LocalStorage.

La prioridad es tener un JS sólido.

1. Estructura básica en HTML
   - [x] - 1.1 Un input de texto y un botón para buscar bebidas por su nombre.
   - [x] - 1.2 Un listado de resultados donde se pinte la imágen y el nombre de la bebida.

2. Búsqueda
   - [x] - 2.1 Click en buscar -> conexión al API de bebidas.
   (www.thecocktaildb.com/api/json/v1/1/search.php?s=margarita)
   - [x] - 2.2 Recoger el texto de la usuaria para construir la URL de búsqueda.
   -2.3 Pintar una tarjeta con la imágen y nombre de la bebida por cada item que coincida con la búsqueda.
   -2.4 Usar una imagen placeholder en caso que la bebida devuelta por la API no tenga una 
   -2.5 Pintar en HTML con innerHTML o DOM.

/// Brainstorming

evento click en botón buscar
   ejecuta la conexión fetch(parámetros???)
   añadir el valor de la búsqueda a la url para que devuelva las bebidas correctas
   render html




3. Favoritos
   -3.1 Click sobre un cocktail -> 
      -3.1.1 Color de fondo y de fuente cambian.
      -3.1.2 Listado de favoritos en la parte izq de la pantalla, bajo el input de búsqueda (se recomienda crear una variable [] para las bebidas favoritas).
      -3.1.3 Las favoritas deben continuar en la página aun si se realiza otra búsqueda.

4. Almacenamiento local
   -4.1 Guardar el listado de favoritos en LS.

5. BONUS. Borrar favoritos
6. BONUS. Afinar maquetación