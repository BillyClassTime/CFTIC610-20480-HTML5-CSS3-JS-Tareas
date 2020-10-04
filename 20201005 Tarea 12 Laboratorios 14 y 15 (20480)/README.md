1. **Nombres y apellidos:** Justo Antonio Garrido Herrador
2. **Fecha:** entrega 4-10-2020
3. **Resumen del Ejercicio:** 
4. **Laboratorios**: 
   
   1. **Laboratorio Módulo 14**: Fichero de Instrucciones: Instructions\20480C_MOD014_LAK.md
   2. **Laboratorio Módulo 15**: Fichero de Instrucciones: Instructions\20480C_MOD015_LAK.md
   4. **Objetivos**: 
      1. Laboratorio Módulo 14: creación de web worker en módulo, tratamiento de eventos con el web worker.
      2. Laboratorio Módulo 15: empaquetado de codigo mediante webpack/babel.
   5. **Pasos**: 
      1. Laboratorio Módulo 14: modificación de JS.
      2. Laboratorio Módulo 15: modificación de configuración npm, webpack y los links a JS en el html (solo lo cambié en index.htm).
5. **Dificultad o problemas presentados y como se resolvieron:**  

   1. En Laboratorio Módulo 14, en Task 6 Punto 10, si bien la imagen se procesó en un web worker, no apareció en gris. Después de borrar cachés, revisar la programación, debugar, opté finalmente por revisar la solución y vi que efectivamente había una línea diferente en grayscale.js en el LAK a la solución, la puse y funcionó:

      ```javascript
              //  erronea en LAK: context.putImageData(imageData, 0, 0);
              context.putImageData(event.data.done, 0, 0);  // OK en solu
      ```

   2. En Laboratorio Módulo 15, tuve que añadir a mano en package.json:

      ```json
        "scripts": {
          "webpack": "webpack"
        }
      ```

   3. También tuve que instalar mediante npm:

      ```sh
      npm install babel-loader@7
      ```

   4. Es posible que haya que crear a mano el directorio dist.

   5. Si no recuerdo mal, al final del laboratorio 15, el proyecto no compiló. Pero puede probar index.htm mediante Archivo -> Ver en Explorador (MS Edge).
6. **Detalles de la entrega:**
   
   1. **Laboratorios**
      1. **Evidencias capturas de pantalla en carpetas**: **MOD * Capturas**. ( ruta: ...\CFTIC610-20480-HTML5-CSS3-JS-Tareas\20201005 Tarea 12 Laboratorios 14 y 15 (20480)\MOD * Capturas).
      2. **Proyectos modificados** : ver carpetas "**MOD * Proyectos**". ( ruta: ...\CFTIC610-20480-HTML5-CSS3-JS-Tareas\20201005 Tarea 12 Laboratorios 14 y 15 (20480)\MOD * Proyectos)

