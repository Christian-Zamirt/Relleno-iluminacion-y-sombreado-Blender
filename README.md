# Relleno-iluminacion-y-sombreado-Blender
 
 En esta parte se tomaron los colores degradados y homogeneos que tienen en el relleno de poligonos 
 
 # RELLENO DE POLIGONOS
 
 Los polígonos son una figura básica dentro de las representaciones y tratamiento de imágenes bidimensionales, su utilización es muy interesante para modelar objetos del mundo real. En un sentido amplio, se define como una región del espacio delimitada por un conjunto de líneas (aristas) y cuyo interior puede estar rellenado por un color o patrón dado.
 
 # Color homogeneo 
 
La homogeneidad también puede predicarse del color por ejemplo : “Pintemos toda la vivienda de un color homogéneo para poder retocar los defectos con mayor facilidad, guardando un poco de pintura”, "Si quieres preparar un color diferente mezclando dos o más tonos, trta de revolver bien la pintura para que quede homogénea"


![homogeneo](https://user-images.githubusercontent.com/72089660/145914645-6db4f0ef-6d68-438c-8084-4696d16eb9c3.PNG)

#  Color degradado

El Degradado es una técnica que está especialmente vinculado con el terreno del diseño gráfico y la maquetación, con todo lo que tiene que ver con la elaboración de imágenes o su modificación. Consiste en combinar dos colores de forma que uno va perdiendo intensidad a medida que el otro la va ganando, realizando una transición cromática suave que puede conseguir resultados muy impactantes.

![Degradado](https://user-images.githubusercontent.com/72089660/145924150-16063767-7085-4e4c-b271-4afa58ddcaa0.PNG)


# Texturas
 
En el campo del modelado 3D el material funciona de una manera similar, es un recubrimiento a modo de capa que se le aplica a un objeto modelado, con el fin de hacerlo mas realista y asi poder comprender la naturaleza de dicho objeto.

![Texturas](https://user-images.githubusercontent.com/72089660/145913767-6457d289-4bf6-4f8d-beba-9060ea34f158.PNG)

![Texturas 2](https://user-images.githubusercontent.com/72089660/145914182-eafb66a7-7e29-4949-b92c-50d47966da0b.PNG)

# ILUMINACIÓN

Desde una perspectiva física, una superficie puede emitir luz por su propia emisión, como focos de luz, o reflejar luz de otras superficies que la iluminan. Algunas superficies pueden reflejar y emitir luz. El color que se ve en un punto de un objeto está determinado por las múltiples interacciones entre las fuentes de luz y superficies reflectivas. Este es un proceso recursivo.

![image](https://user-images.githubusercontent.com/72089660/145925485-dd9c817f-7efb-4831-934c-263c53b8a83f.png)

Esferas iluminadas

![Esferas 2](https://user-images.githubusercontent.com/72089660/145927277-7761df95-2f6f-46bf-b53f-41e9c3cde61c.PNG)

# SOMBREADO

También conocido como sombreado facetadon o plano, este método aplica un modelo de iluminación sólo una vez, el cual permite determinar un valor de Iλ para un polígono. 

![asdfgh](https://user-images.githubusercontent.com/72089660/145932421-a0de7bb2-f791-4bcc-8da0-d062eafd127a.png)

# Sombreado interpolado

Este método es muy fácil de usar en un algoritmo de línea de barrido que interpola el valor de z en un tramo a partir de valores de z interpolados que se calculan para los puntos extremos del tramo.
Es recomendable usar una ecuación de diferencias para aumentar la eficiencia en la determinación del valor de z en cada pixel. Aunque la interpolación z es físicamente correcta (suponiendo que el polígono es plano), observe que el sombreado interpolado no lo es, ya que sólo aproxima la evaluación del modelo de iluminación en cada punto del polígono.

![sombreado interpolado](https://user-images.githubusercontent.com/72089660/145932590-1cebc960-c225-4cdf-82d9-0b118f3b7721.PNG)



