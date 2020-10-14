# Proyecto nodejs con clases

En este proyecto haremos una modificación del proyecto anterior definiendo los polígmonos como 
clases para calcular su perímetro y su área. Para ello hemos creado una carpeta nueva llamada **clases**
en la que hemos añadido los archivos .ts con las clases.

Para introducir las clases en el index añadimos en la cabecera la ruta del archivo en el que se encuentra al clase
por ejemplo: **import { Triangulo } from '../clases/triangulo'** y en el archivo de las clases al final 
añadimos  **export{Triangulo}** para poder acceder al archivo desde el index.


Para calcular el área y el perímetro del círculo hemos usado la propiedad **Math.PI** 
 información buscada en: https://developer.mozilla.org/es/docs/Web/JavaScript/Referencia/Objetos_globales/Math/PI