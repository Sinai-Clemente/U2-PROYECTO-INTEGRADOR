># U2-PROYECTO-INTEGRADOR

## Proyecto: Animación frame X frame en base a una referencia de "walk cycle"
<div align="justify"> 
  
### Introducción
La animación frame por frame es una técnica fundamental dentro del mundo de la animación digital, que consiste en crear movimiento mediante la sucesión de imágenes estáticas. En este proyecto se desarrolla un ciclo de caminata (walk cycle), el cual representa uno de los ejercicios básicos más importantes para comprender el movimiento humano.

Utilizando el software Blender en su entorno 2D (Grease Pencil), se construye una animación basada en una referencia visual, permitiendo analizar y replicar las fases del movimiento de una caminata. Este proyecto integra principios de animación, coordinación visual y, en algunos casos, fundamentos matemáticos relacionados con el tiempo, la velocidad y la posición.

### Objetivo General
Desarrollar una animación 2D tipo walk cycle mediante la técnica de animación frame por frame en Blender, utilizando una referencia visual, con el fin de comprender y aplicar los principios básicos del movimiento, la secuencia de fotogramas y la coordinación temporal.


### La Base Matemática del Proyecto
En este proyecto se pueden identificar algunos conceptos matemáticos básicos:<br><br>
•	Tiempo y fotogramas (FPS):
La animación se basa en una secuencia de imágenes llamadas fotogramas. La relación entre tiempo y fotogramas se puede expresar como:<br>
t= n/FPS<br>
Donde:<br>
o	t = tiempo en segundos <br>
o	n = número de fotogramas <br>
o	FPS = fotogramas por segundo <br><br>
•	Movimiento y posición:
El desplazamiento del personaje puede representarse como un cambio de posición en el eje X (horizontal) a lo largo del tiempo. <br><br>
•	Velocidad constante (opcional):
Si el personaje camina de forma uniforme, se puede considerar:<br>
v=d/t <br><br>
•	Ciclos y repetición:
El walk cycle es un movimiento periódico, lo que implica repetición de patrones en intervalos iguales<br>

### Desarrollo del Proyecto
El desarrollo del proyecto se llevó a cabo en diferentes etapas:

1. Selección y análisis de referencia<br>
Se utilizó una referencia visual de un ciclo de caminata para identificar las poses principales del movimiento. Estas incluyen:<br>
•	Contacto (cuando el pie toca el suelo) <br>
•	Paso <br>
•	Subida <br>
•	Bajada <br>
Este análisis permitió comprender cómo se distribuye el peso y el movimiento del cuerpo.<br>
<img width="1408" height="768" alt="image" src="https://github.com/user-attachments/assets/893bacfe-4bac-44cc-a9db-10814d5a4021" />

2. Configuración del entorno en Blender<br>
Se inició el programa Blender en modo de animación 2D.
<img width="921" height="489" alt="image" src="https://github.com/user-attachments/assets/41f74c95-4737-4da8-b8c1-79172ddc9db2" />

Posteriormente, se "Elimino" el stroke que tiene al amomneto de abrir el programa, para empezar con uno desde cero. 
<img width="921" height="489" alt="image" src="https://github.com/user-attachments/assets/b4065796-9438-4711-9dde-c16da539dcb5" />

Despues  se agregó un objeto "Grease Pencil" en "Blanco", el cual servirá como base para realizar los dibujos.
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/4d9557ed-e038-4101-9363-7f40084cc05c" />


4. Creación de materiales
Se configuraron diferentes materiales para el proyecto, los cuales se utilizaron para trazar y colorear la animación. Cada material fue asignado con un color específico en formato hexadecimal.

•	Material 01: Trazo (#402C20FF)
•	Material 02: Relleno (#674633FF)
•	Material 03: Relleno (#8E664FFF)
•	Material 04: Relleno (#000000FF)
•	Material 05: Relleno (#9E2303FF)
•	Material 06: Relleno (#FFFFFF)

Para esta configuración le dimos en "Material" y eliminamos el contenido que tiene en "Eliminar(-). 
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/c4a598a1-9d75-422c-ab56-62f851ba62c9" />

Posteriormente le damos en "Agregar (+)" y en "Nuevo". 
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/55b1bd43-9ff2-485e-bb24-13e0ac7c8dc0" />

En seguida le cambiamos el "Nombre" por "01".
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/a76d542d-51d9-46eb-a974-45d76fb2b4ba" />

Después seleccionamos la casilla de "Trazo" y en la opcion "Color base" agregamos el color.
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/6d2daa2d-e5da-4819-b41d-687531139529" />

Para crear los demás materiales seguimos los mismos pasos. Solo que a partir de este material seleccionaremos la casilla de “Relleno” y en la opción "Color base" agregamos los colores a ocupar. 
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/5cc539f9-f547-4427-bc90-14eb56af56a4" />

4. Importación de imagen de referencia
Se agregó una imagen de referencia desde la opción “Agregar → Imagen → Referencia”.
<img width="921" height="487" alt="image" src="https://github.com/user-attachments/assets/edb27378-0e37-4398-8c21-5a150a29c415" />

Esta imagen fue escalada y se redujo su opacidad al 0.5, permitiendo dibujar encima de ella con mayor precisión. Para ello vamos a “Vacío -> Imagen” y seleccionaremos la casilla “Opacidad” y le pondremos "0.5".
<img width="921" height="489" alt="image" src="https://github.com/user-attachments/assets/ba77244c-c8d8-40b1-b8de-9b804955e226" />

6. Animación por fotogramas
La animación se realizó mediante una secuencia de 8 dibujos diferentes. Cada dibujo se colocó cada 3 fotogramas dentro de una línea de tiempo de 24 fotogramas.
El proceso fue el siguiente:

•	Dibujar el primer fotograma
•	Avanzar 3 cuadros
•	Dibujar el siguiente
•	Repetir el proceso hasta completar los 8 dibujos


<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/dcc0a776-cb7e-4361-abde-e5f76a470d3d" />

7. Organización por capas
Se selecciono el "Stroke", y se renombro por "Mascota".
<img width="921" height="487" alt="image" src="https://github.com/user-attachments/assets/19893f55-065f-4560-8a59-7098507b55bc" />

Se crearon dos capas principales:
•	Capa de Relleno.
Para ello iremos al "Stroke", y seleccionaremos en "Capas", y podremos ver que ya tiene la primera capa, la cual la renombraremos por "Relleno".
<img width="921" height="490" alt="image" src="https://github.com/user-attachments/assets/0394c48b-90cd-452d-a46d-e516d94afbe8" />
•	Capa de Trazos.
Ahora creamos una nueva "Capa" para hacer los trazos le damos en “Agregar una nueva capa (+)”, y la renommbraremmos por Trazo. 
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/ded5ac03-ee69-45a0-853f-85bbbb8a150b" />
Esto permitió trabajar de forma ordenada y separar los elementos del dibujo.

8. Proceso de dibujo
Se utilizó el modo dibujo para trazar la figura de la mascota.
<img width="921" height="491" alt="image" src="https://github.com/user-attachments/assets/44ea8ad3-e96c-4a08-87dc-7792f3da1be3" />

Después iremos a "Materiales" y seleccionamos el "Material 01" y en la parte de "Intensidad" la aumentamos a 1.000 y para el grosor del trazo en la parte de "Tamaño" a 0.015m.
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/1580a2f2-2b14-4b9a-af7d-040020384555" />

Una vez tenido configurado lo anterior, empezaremos a trazar, para ello iremos a la opción “Marco”, y le daremos clip izquierdo dejándolo presionado. Y podemos observar que se emplean diferentes herramientas, donde ocuparemos solo estas 3:
•	Arco: para curvas suaves
•	Curva: para formas más complejas
•	Línea poligonal: para detalles
<img width="921" height="490" alt="image" src="https://github.com/user-attachments/assets/0e798745-504d-43b8-93ee-8db5fd36520d" />

9. Aplicación de color
Una vez terminado el trazo, se procedió a rellenar el dibujo utilizando los materiales previamente creados. Esto permitió darle vida y detalle a la ilustración. Para ello iremos al "Stroke" y cambiaremos a "Relleno". 
<img width="921" height="486" alt="image" src="https://github.com/user-attachments/assets/5cbae5c9-746f-40d6-aa26-aad33bd6b1e6" />

Después nos vamos a "Material" y seleccionaremos el "Material" a ocupar para el relleno, dandole clip izquietdo sostenido en la herramienta de "Marco" a "línea poligonal".
<img width="921" height="491" alt="image" src="https://github.com/user-attachments/assets/2130be94-3098-4021-b1d6-a20d09b19ea7" />
El proceso 7 y 8 lo repetimos para los demás dibujos.  




10. Ajuste de posición
Cada dibujo fue ajustado en modo edición para asegurar la continuidad del movimiento. Se utilizó la herramienta de mover (G) para alinear correctamente cada fotograma.

11. Aplicación de efectos
Se añadieron efectos visuales para mejorar la calidad de la animación:
•	Efecto de luz (ribete)
•	Sombra
También se configuró el color de fondo (World) para complementar la animación.

 
Resultado
Como resultado final, se obtuvo una animación 2D fluida de una mascota, lograda mediante el uso de dibujo cuadro por cuadro, organización por capas y aplicación de efectos visuales.
 <img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/9db72aa4-cf49-4dc5-9a7c-e111e341753c" />


</div>
