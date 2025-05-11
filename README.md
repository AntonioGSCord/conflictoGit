# conflictoGit
Creado para ejercicio de entornos
Lo primero que hice fue crear 4 archivos txt para simular el conflicto y hacer un commit es decir una copia en local
y un push, una copia en remoto de esos archivos.
tenía otro repositorio pero decidí crear este solo para este ejercicio y lo hice con una cuenta distinta con lo cual tuve varios fallos
El primero fue que al crear el repositorio lo hice privado con lo cual al sincronizarlo con vsc a través de la url no era posible, no lo encontraba al ser privado. Cambiando la visibilidad a público solucioné ese problema.
Luego arrastré los archivos al visual he hice Haz clic en el "+" de la parte superior de la sección "Cambios" para añadirlos todos de una vez.
Hice un commit inicial y luego sincronizé con el repositorio remoto
Me saltó un mensaje que decía que no tenía permisos directos para hacer push a la rama en la que estaba actualmente
Miré y vi que no tenía ninguna regla de protección de ramas activa en el repositorio en GitHub en ese momento, cerré la sesión que tenía abierta y abría la sesión con el usuario nuevo que me hice, después lo que hice fue abrir en Windows el Administrador de credenciales y fuí a la sección "Credenciales de Windows", busqué cualquier entrada genérica relacionada con "git", "GitHub", o la URL del repositorio y la eliminé.
Una vez hecho esto al iniciar sesión Git Credential Manager guardo las credenciales y ya si pude vincular mi cuenta nueva con vsc.
Lo siguiente fue sincronizar los cambios que tenía pendientes que lo hice con un icono de dos flechas circulares que hay abajo a la izquierda