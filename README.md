# Module 5: Communicating with a Remote Server

**Nombre:** Francisco Javier Moreno Quevedo

**Fecha:** 28/09/2020

**Resumen del Ejercicio:** El laboratorio se compone de tres ejercicios. En el ejercicio 1 Se añade código JavaScript para recivir lista de las ponencias del servidor. En el ejercicio 2 Se crean dos checkbox que filtraran esas ponencias y en el ejercicio 3

**Dificultad o problemas presentados y como se resolvieron:** Ninguna

- Ejercicio 1

  - comprobamos que el json de las ponencias no esta en HardCopy en el fichero
  - Creamos la funcion **downloadSchedule** que se conectará con el server y recibira las ponencias en formato json
  - Aplicamos el control de errores a esa funcion

- Ejercicio 2

  - Creamos la funcion **saveStar** que se conectará con el server y enviara la sesion que ha reservado el participante
  - SI esa sesion tiene mas de 50 participantes aparece un mensaje

- Ejercicio 3

  - Sustituimos la función **downloadSchedule** por codigo que utiliza la funcion **Fetch**

  - Al igual que con la funcion **saveStar**

    