# TP1_2026_Gonzalez\
Agustín González\
gonzalezagustin512@gmail.com\
21612\

Bruno Palacios\
12345\
palaciosbruno@hotmail.com\
Responda entre líneas a cada una de las siguientes preguntas: 
 
1) ¿Qué ocurrió durante el merge?\
 Ocurrió un conflicto al hacer el merge. el git unir automáticamente la rama AgustinGonzalez con la rama main, pero las ramas tenían cambios diferentes en el mismo archivo.\
 
2) ¿Por qué ocurrio?\
se "chocaron" los archivos readme al editarse, como git no puede adivinar qué información es la que debe prevalecer, deja que lo hagas manualmente.\ 
 
3) ¿Cómo lo soluciono? \
abro el archivo y edito el contenido luego un git add y un git comit\
 
4) Que significan los marcadores <<<<<<<, ======= y >>>>>>>? 
=======\
Los marcadores delimitan las versiones en conflicto para que el usuario pueda editarlas/

<<<<<<< HEAD: Indica el inicio de los cambios en la rama donde estás parado actualmente.

>>>>>>> [NombreRama]: Señala el final de los cambios que provienen de la rama que se intenta integrar.

======= (El divisor):Su función es dividir los cambios de la rama base de los cambios de la rama entrante. Sin este separador, no habría forma de identificar con precisión dónde termina una versión y comienza la otra, lo que imposibilitaría distinguir qué líneas pertenecen a cada propuesta para resolver el conflicto.


