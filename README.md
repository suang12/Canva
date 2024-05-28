# Canva_html

- Nos permite crear animaciones y juegos 2D en el navegador
- En el navegador el codigo se representa de manera secuencial 
- para utilizar el codigo JS, debemos esperar a que todos los elementos HTML hayan sido creados antes de ser utilizados 

- Alternativas:
    - Colocar el script en la parte inferior de la pagina
    - Utilizar un detector de eventos que nos indique cuando los elementos han sido creados. (evento onload desde el body o script)

- Se crea una variable canvas por medio del identificador de etiquetas 
- Se verifica si la variable se creo correctamente 
- En realidad se trabaja con el **Contexto** de canvas 2D. Se crea una variable **ctx** con la cual

