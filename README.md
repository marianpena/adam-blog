# MI Adam Blog web
- Usa el siguiente tema de Jekyll:
jekyllthemes.org/themes/adam-blog/
- Crea el repositorio en GITHUB tal como se explica en esta unidad, añadiendo a mano los ficheros del .zip de este tema en Eclipse. A dicho repositorio tenemos que darle el nombre adam-blog .
Después de crear la GitHub Page, tarda un rato en actualizarse.
 e pueden borrar alguno de los posts existentes, o modificarlos. Solo es necesario borrar o modificar alguno de los ficheros de la carpeta _posts . Prueba a borrar alguno.
- Para añadir un post nuevo, hay que crear un nuevo archivo en la carpeta _posts, pero es imprescindible ponerle una fecha y terminar con extensión .markdown, como lo tienen el resto de posts. Por ejemplo: 
2019-12-01-Bienvenidos-a-mi-cuenta-de-GitHub.markdown
- Para añadir una foto de fondo a este post nuevo, el contenido de dicho fichero debe empezar por, al menos, este contenido: (copiado de otro post ya existente)
---
img: post-1.jpg # Add image post (optional)
---
La imagen a la que hace referencia (en este caso post-1.jpg) debe existir en la carpeta assets/img
- Para añadir una imagen dentro del post hay que hacer lo siguiente:
Dejar la imagen que queramos añadir (yosh-ginsu.jpg) en la carpeta assets/img
Añadir en el fichero del nuevo post, el código necesario para que se muestre la imagen. Lo podemos copiar de algún otro post. Por ejemplo:
![Yosh Ginsu]({{site.baseurl}}/assets/img/yosh-ginsu.jpg)
Ten en cuenta que siempre tarda un rato en actualizarse.
-En Settings -> Pages Elegimos la rama main Pulsamos en el botón Save 
-web https://marianpena.github.io/adam-blog/
