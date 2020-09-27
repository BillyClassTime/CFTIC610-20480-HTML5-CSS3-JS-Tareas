1. **Nombres y apellidos:** Justo Antonio Garrido Herrador
2. **Fecha:** entrega 27-9-2020
3. **Resumen del Ejercicio:** 
   1. **Laboratorio Módulo 5**: Fichero de Instrucciones: Instructions\20480C_MOD05_LAK.md (entero). 
      1. **Objetivos**: 
         1. Recuperar datos mediante AJAX con formato JSON y el tratamiento de errores, programación y pruebas. 
         2. Enviar y recuperar datos mediante AJAX con formato JSON, programación y pruebas. 
         3. Rehacer la llamada mediante async / await / fetch, (y manejando el asincronismo). 
      2. **Pasos**: 
         1. Creación y llamada de función AJAX (XMLHttpRequest), tratamiento de datos obtenidos(JSON.parse), creación de elementos DOM (createElement(), appendChild()...), tratamiento de errores en AJAX.
         2. Creación y llamada de función AJAX (XMLHttpRequest), tratamiento de datos obtenidos(JSON.parse).
         3. Redefinición como función asincrona de downloadSchedule, llamada en espera: await fetch y tratamiento de datos con await response.json(); lo mismo para saveStar; programación y pruebas.
   2. **Laboratorio Módulo 6**: Fichero de Instrucciones: Instructions\20480C_MOD06_LAK.md
      1. **Objetivos**:
         1. Mejorar el aspecto gráfico del menú.
         2. Mejorar el enlace de registro en la conferencia pasando de ser un enlace a ser una imagen con efectos.
         3. Mejorar la página "about" introduciendo columnas, primera letra del párrafo en grande, sangrado en primera línea y estilo para citas.
      2. **Pasos**:  En los tres casos, añadiendo estilos.
   3. **Laboratorio Módulo 7**: Fichero de Instrucciones: Instructions\20480C_MOD07_LAK.md
      1. **Objetivos**: encapsultar el código en clases Javascript.
      2. **Pasos**:  eliminar la programación actual, importar clases, crear clase nueva y utilizar otras ya generadas.
4. **Dificultad o problemas presentados y como se resolvieron:** 
   1. En caso de pérdida de acceso a internet antes de al menos el primer "Start Without Debugging", la compilación del proyecto y la ejecución en Edge fallan, sin que indique (al menos aparentemente) que es por la falta de acceso a Internet. Se resuelve restaurando el acceso a Internet (fue debido a que la Wifi del portátil entró en modo de suspensión o que la Wifi estaba muy ocupada) y volviendo a intentar.
   2. Para evitar problemas de longitud de ruta NTFS, la reducí recortando nombres de las carpetas en las que están los proyectos y subí cada proyectos como un ZIP.
   3. En el laboratorio 6, después de modificar los CSS, hizo falta cerrar y volver a abrir Edge y actualizar mediante CTRL - F5 para ver cambios en CSS en todas las páginas afectadas. No descarto que pueda llegar a ser necesario borrar la cache de Edge y/o cerrarlo y volver a lanzar el proyecto en Visual Studio por segunda vez.
   4. En el laboratorio 7, no se construía bien la página y tuve que mover los métodos dentro de la clase. Es debido a que en el paso 8 de la Task 1, el comentario "//TODO: Add methods" está fuera de la clase.
5. **Detalles de la entrega:**
   1. **Laboratorio Módulo 5**
      1. **Proyectos modificados con Visual Studio 2019 en carpeta: MOD5 Proyectos, en ZIPs**: Exercise 1.zip, Exercise 2.zip, Exercise 3.zip. (ruta: ...\CFTIC610-20480-HTML5-CSS3-JS-Tareas\20200925 Tarea 6 Laboratorios 5, 6 y 7 (20480)\MOD5 Proyectos)
      2. **Evidencias capturas de pantalla en carpeta**: **MOD5 Capturas**. (ruta: ...\CFTIC610-20480-HTML5-CSS3-JS-Tareas\20200925 Tarea 6 Laboratorios 5, 6 y 7 (20480)\MOD5 Capturas)
      3. **Observaciones**: en "20480C_MOD05_LAK.md" se indica al final: *"**Results**: After completing this exercise, you will have refactored the JavaScript code that sends and receives data to use the **jQuery ajax** method."* Pero a simple vista parece un error la indicación de jQuery pues ni se incluye en el JS la librería jQuery ni aparecen llamadas a $.
   2. **Laboratorio Módulo 6**: 
      1. **Proyectos modificados con Visual Studio 2019 en carpeta: MOD6 Proyectos, en ZIPs**: Exercise 1.zip, Exercise 2.zip, Exercise 3.zip. (ruta: ...\CFTIC610-20480-HTML5-CSS3-JS-Tareas\20200925 Tarea 6 Laboratorios 5, 6 y 7 (20480)\MOD6 Proyectos)
      2. **Evidencias capturas de pantalla en carpeta**: **MOD6 Capturas**. (ruta: ...\CFTIC610-20480-HTML5-CSS3-JS-Tareas\20200924 Tarea 5 MOC 20480 (Módulos del 4 al 7)\MOD6 Capturas)
   3. **Laboratorio Módulo 7**: 
      1. **Proyecto modificado con Visual Studio 2019 en carpeta: MOD7 Proyectos, en ZIP**: Exercise 1.zip. (ruta: ...\CFTIC610-20480-HTML5-CSS3-JS-Tareas\20200925 Tarea 6 Laboratorios 5, 6 y 7 (20480)\MOD7 Proyectos)
      2. **Evidencia captura de pantalla**: **MOD7 Capturas**. (ruta: ...\CFTIC610-20480-HTML5-CSS3-JS-Tareas\20200924 Tarea 5 MOC 20480 (Módulos del 4 al 7)\MOD7 Capturas) 

