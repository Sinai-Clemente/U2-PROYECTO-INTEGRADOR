># U2-PROYECTO-INTEGRADOR

## Proyecto: Animación frame X frame en base a una referencia de "walk cycle"
<div align="justify"> 
  
## Introducción
La animación frame por frame es una técnica fundamental dentro del mundo de la animación digital, que consiste en crear movimiento mediante la sucesión de imágenes estáticas. En este proyecto se desarrolla un ciclo de caminata (walk cycle), el cual representa uno de los ejercicios básicos más importantes para comprender el movimiento humano.

Utilizando el software Blender en su entorno 2D (Grease Pencil), se construye una animación basada en una referencia visual, permitiendo analizar y replicar las fases del movimiento de una caminata. Este proyecto integra principios de animación, coordinación visual y, en algunos casos, fundamentos matemáticos relacionados con el tiempo, la velocidad y la posición.

## Objetivo General
Desarrollar una animación 2D tipo walk cycle mediante la técnica de animación frame por frame en Blender, utilizando una referencia visual, con el fin de comprender y aplicar los principios básicos del movimiento, la secuencia de fotogramas y la coordinación temporal.


## La Base Matemática del Proyecto
En este proyecto se pueden identificar algunos conceptos matemáticos básicos:<br>
•	Tiempo y fotogramas (FPS):
La animación se basa en una secuencia de imágenes llamadas fotogramas. La relación entre tiempo y fotogramas se puede expresar como:<br>
t= n/FPS<br>
Donde:<br>
t = tiempo en segundos <br>
n = número de fotogramas <br>
FPS = fotogramas por segundo <br><br>
•	Movimiento y posición:
El desplazamiento del personaje puede representarse como un cambio de posición en el eje X (horizontal) a lo largo del tiempo. <br><br>
•	Velocidad constante (opcional):
Si el personaje camina de forma uniforme, se puede considerar:<br>
v=d/t <br><br>
•	Ciclos y repetición:
El walk cycle es un movimiento periódico, lo que implica repetición de patrones en intervalos iguales<br>

## Desarrollo del Proyecto
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
Posteriormente, se "Elimino" el stroke que tiene al momento de abrir el programa, para empezar con uno desde cero.
<img width="921" height="489" alt="image" src="https://github.com/user-attachments/assets/b4065796-9438-4711-9dde-c16da539dcb5" />
Después  se agregó un "Grease Pencil" en "Blanco", el cual servirá como base para realizar los dibujos.
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/4d9557ed-e038-4101-9363-7f40084cc05c" />

3. Creación de materiales<br>
Se configuraron diferentes materiales para el proyecto, los cuales se utilizaron para trazar y colorear la animación. Cada material fue asignado con un color específico en formato hexadecimal.<br>
•	Material 01: Trazo (#402C20FF)<br>
•	Material 02: Relleno (#674633FF)<br>
•	Material 03: Relleno (#8E664FFF)<br>
•	Material 04: Relleno (#000000FF)<br>
•	Material 05: Relleno (#9E2303FF)<br>
•	Material 06: Relleno (#FFFFFF)<br>
Para esta configuración le dimos en "Material" y eliminamos el contenido que tiene en "Eliminar (-)".
<img width="921" height="489" alt="image" src="https://github.com/user-attachments/assets/5e777bd6-534b-4bae-a39c-a76109a6ff34" />
Posteriormente le damos en "Agregar (+)" y en "Nuevo". <br>
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/55b1bd43-9ff2-485e-bb24-13e0ac7c8dc0" />
En seguida le cambiamos el "Nombre" por "01".<br>
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/a76d542d-51d9-46eb-a974-45d76fb2b4ba" />
Después seleccionamos la casilla de "Trazo" y en la opción "Color base" agregamos el color.<br>
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/6d2daa2d-e5da-4819-b41d-687531139529" />
Para crear los demás materiales seguimos los mismos pasos. Solo que a partir de este material ya no seleccionaremos la casilla de "Trazo", si no que seleccionaremos la casilla de “Relleno” y los colores a ocupar.
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/5cc539f9-f547-4427-bc90-14eb56af56a4" />

4. Importación de imagen de referencia<br>
Se agregó una imagen de referencia desde la opción “Agregar → Imagen → Referencia”.
<img width="921" height="487" alt="image" src="https://github.com/user-attachments/assets/edb27378-0e37-4398-8c21-5a150a29c415" />
Esta imagen fue escalada y se redujo su opacidad al 0.5, permitiendo dibujar encima de ella con mayor precisión. Para ello vamos a “Vacío -> Imagen” y seleccionaremos la casilla “Opacidad” y le pondremos "0.5".
<img width="921" height="489" alt="image" src="https://github.com/user-attachments/assets/ba77244c-c8d8-40b1-b8de-9b804955e226" />

5. Animación por fotogramas<br>
La animación se realizó mediante una secuencia de 8 dibujos diferentes. Cada dibujo se colocó en cada 3 fotogramas dentro de una línea de tiempo de 24 fotogramas.<br><br>
El proceso fue el siguiente:<br>
Primero iremos a la opción "Tipo de editor" y seleccionaremos "línea de tiempo".
 <img width="921" height="489" alt="image" src="https://github.com/user-attachments/assets/bbe85343-3b62-4fa2-adb8-fe9eabf84ec5" />
Posteriormente en el apartado de fin lo cambiamos a 24. <br>
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/dcc0a776-cb7e-4361-abde-e5f76a470d3d" />
Una vez de haber terminado de configurar lo anterior, comenzamos con lo siguiente: <br>
•	Dibujar y rellenar el primer fotograma.<br>
•	Avanzar 3 cuadros.<br>
•	Dibujar y rellenar el siguiente.<br>
•	Repetir el proceso hasta completar los 8 dibujos.<br><br>

A continuación se explicara a detalle el proceso de dibujo y relleno del dibujo. <br>
A. Organización por capas<br>
Se selecciono el "Stroke", y se renombro por "Mascota".<br>
<img width="921" height="487" alt="image" src="https://github.com/user-attachments/assets/19893f55-065f-4560-8a59-7098507b55bc" />
Se crearon dos capas principales:<br>
•	Capa de Relleno.<br>
Para ello iremos al "Stroke", y seleccionaremos "Capas", y podremos ver que ya tiene la primera capa, la cual la renombraremos por "Relleno".<br>
<img width="921" height="490" alt="image" src="https://github.com/user-attachments/assets/0394c48b-90cd-452d-a46d-e516d94afbe8" />
•	Capa de Trazos.<br>
Ahora creamos una nueva "Capa" para hacer los trazos, para crear esta nueva capa le damos en “Agregar una nueva capa (+)”, y la renombraremos por "Trazo". <br>
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/ded5ac03-ee69-45a0-853f-85bbbb8a150b" />
Esto permitirá trabajar de forma ordenada y separar los elementos del dibujo.<br>

B. Proceso de dibujo<br>
Se utilizó el modo dibujo para trazar la figura de la mascota.<br>
<img width="921" height="491" alt="image" src="https://github.com/user-attachments/assets/44ea8ad3-e96c-4a08-87dc-7792f3da1be3" />
Después iremos a "Materiales" y seleccionamos el "Material 01" y en la parte de "Intensidad" la aumentaremos a 1.000 y en "Tamaño" a 0.015m para el grosor del trazo.<br>
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/1580a2f2-2b14-4b9a-af7d-040020384555" />
Una vez de haber configurado lo anterior, empezaremos a trazar, para ello iremos a la opción “Marco”, y le daremos clip izquierdo dejándolo presionado. Y podemos observar que se emplean diferentes herramientas, donde ocuparemos solo estas 3:<br>
•	Arco: para curvas suaves.<br>
•	Curva: para formas más complejas.<br>
•	Línea poligonal: para detalles.<br>
<img width="921" height="490" alt="image" src="https://github.com/user-attachments/assets/0e798745-504d-43b8-93ee-8db5fd36520d" />

C. Aplicación de color<br>
Una vez terminado el trazo, se procedió a rellenar el dibujo utilizando los materiales previamente creados. Esto permitirá darle vida y detalle a la ilustración. Para ello iremos al "Stroke" y cambiaremos a "Relleno". <br>
<img width="921" height="486" alt="image" src="https://github.com/user-attachments/assets/5cbae5c9-746f-40d6-aa26-aad33bd6b1e6" />

Después nos vamos a "Material" y seleccionaremos el Material a ocupar para el relleno. Posteriormente le damos clip izquierdo sostenido en la herramienta de "Marco" y seleccionamos "línea poligonal".<br>
<img width="921" height="491" alt="image" src="https://github.com/user-attachments/assets/2130be94-3098-4021-b1d6-a20d09b19ea7" />
Rellenamos nuestra imagen. <br>
<img width="921" height="489" alt="image" src="https://github.com/user-attachments/assets/ee8cc9fa-4c2b-4c83-bd9a-00639d97e1bd" />
Todo este proceso lo repetimos para los demás dibujos.  <br>
<img width="921" height="487" alt="image" src="https://github.com/user-attachments/assets/5e19eec0-15a6-4aeb-a123-db01f20e5f60" />

6. Ajuste de posición<br>
Cada dibujo fue ajustado en "Modo edición" para asegurar la continuidad del movimiento. Se selecciono el fotograma con la "Tecla A"  y se utilizó la "Tecla G y X" para mover la imagen y alinear correctamente cada fotograma.
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/c15ede07-a9a0-4a89-846d-6ef9f2e7aba3" />
Este proceso lo realizamos con el resto de los fotogramas. <br>
<img width="921" height="489" alt="image" src="https://github.com/user-attachments/assets/5c99d06d-724d-4c98-a910-8a0bb7a4e23a" />
Una vez terminado, apagaremos temporalmente la imagen de referencia, en la opción "Ocultar en vistas".<br>
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/9989c3de-bb4c-479c-b882-dfa22bb13a38" />

7. Aplicación de efectos<br>
Se cambio a "Modo objeto". <br>
Posteriormente se añadieron efectos visuales para mejorar la calidad de la animación:<br>
•	Efecto de luz (ribete)<br>
Para ponerle efecto de luz, vamos primero a la parte de "Efectos".<br>
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/6fd59166-44b5-4186-ab03-40f47d652283" />
Damos clic en "Efecto -> Ribete". <br>
<img width="921" height="489" alt="image" src="https://github.com/user-attachments/assets/c95e0eff-f1cb-40a8-9086-d21c8be1d478" />
Después entramos al "Render".<br>
<img width="921" height="491" alt="image" src="https://github.com/user-attachments/assets/a8f0234e-2d85-4f2c-9cca-c068730a6de3" />
Le pondremos un poco de luz.<br>
<img width="921" height="486" alt="image" src="https://github.com/user-attachments/assets/54519528-f175-40b8-ae7d-4a4ecbe2b8aa" />
•	Sombra<br>
En este mismo apartado de “Efecto” le agregamos un "Nuevo efecto" dándole clip en “Sombra”. <br>
<img width="921" height="487" alt="image" src="https://github.com/user-attachments/assets/3f3e62f0-aba9-4be8-bbdd-8889d1d200ea" />
Y la configuramos de esta forma. <br>
<img width="921" height="485" alt="image" src="https://github.com/user-attachments/assets/1bad17a0-4afb-4488-b8b9-5403b325b271" />
También se configuró el color de fondo (World) para complementar la animación.  Para ello iremos al apartado de “Entorno”.<br>
<img width="921" height="489" alt="image" src="https://github.com/user-attachments/assets/f7cdd374-c92d-41a1-bf85-5a698f0dca89" /> <br>
Después le damos clic en “Color” y seleccionaremos nuestro color. <br>
<img width="921" height="490" alt="image" src="https://github.com/user-attachments/assets/c3fbdea0-2d99-4c47-b4ff-3d7ef9d7fdbb" /> <br>

Resultado<br>
Como resultado final, se obtuvo una animación 2D fluida de una mascota, lograda mediante el uso de dibujo cuadro por cuadro, organización por capas y aplicación de efectos visuales.<br>
 <img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/9db72aa4-cf49-4dc5-9a7c-e111e341753c" />


</div>
