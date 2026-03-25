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
Se configuró el entorno de trabajo en 2D utilizando Grease Pencil.<br>
Se definieron aspectos como:<br>
•	FPS (12 o 24) <br>
•	Espacio de trabajo<br> 
•	Línea de tiempo <br>
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/dcc0a776-cb7e-4361-abde-e5f76a470d3d" />

3. Creación de poses clave (Keyframes)<br>
Se dibujaron las poses principales del ciclo de caminata:<br>
•	Primer contacto <br>
•	Pose opuesta <br>
•	Paso intermedio <br>
Estas poses sirven como base estructural de la animación.<br>
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/3533b5da-13ed-4633-bc38-1c597c612b3e" />


4. Interpolación (In-betweens)<br>
Se agregaron dibujos intermedios entre las poses clave para suavizar el movimiento y hacerlo más natural.<br>
<img width="921" height="487" alt="image" src="https://github.com/user-attachments/assets/4ea796bb-78b1-438e-911c-d226ca7d5dc0" />


5. Ajustes y refinamiento<br>
Se revisó la animación para mejorar:<br>
•	Fluidez <br>
•	Ritmo <br>
•	Proporciones <br>
Se realizaron correcciones en posiciones y tiempos.<br>
<img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/22025e91-f973-45b2-a66a-aaf4f40e366e" />


6. Creación del ciclo continuo (loop)<br>
Se verificó que el primer y último fotograma coincidieran para lograr una animación continua sin cortes.<br>
<img width="921" height="491" alt="image" src="https://github.com/user-attachments/assets/6dd4ef41-ca0b-4f96-9c98-84a0fbdd261c" />

7. Creación de efectos<br>
Se agrego sombra y luz al dibujo.<br>
<img width="921" height="489" alt="image" src="https://github.com/user-attachments/assets/848fc651-ccbb-413a-b9a6-6cc981867a6e" />

9. Creación del mundo<br>
Se le agrefo un fondo. <br>
  <img width="921" height="490" alt="image" src="https://github.com/user-attachments/assets/3582d168-21fd-4df4-8a7f-56e0d90c9025" />
 
 Ejecución <br>
 <img width="921" height="488" alt="image" src="https://github.com/user-attachments/assets/9db72aa4-cf49-4dc5-9a7c-e111e341753c" />


</div>
