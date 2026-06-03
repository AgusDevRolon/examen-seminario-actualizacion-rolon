# Entrega Examen - Aprendizaje Automático (Tema 3)

## Ejercicio 5 (Archivos: sistema.js e index.html)

### Requisitos previos
Tener Node.js instalado en el sistema.

### Pasos para ejecutar:
1. Abrir una terminal en la carpeta donde se encuentra `sistema.js`.
2. Ejecutar `npm install @tensorflow/tfjs-node` para instalar la dependencia del modelo.
3. Iniciar el backend ejecutando el comando: `node sistema.js`
4. Confirmar en la consola que el servidor corre en el puerto 8008.
5. Abrir el archivo `index.html` en cualquier navegador web.
6. Hacer clic en "Entrenar modelo" para observar la gráfica de pérdida (MSE) y luego probar predicciones para `y = 2x - 3`.

## Ejercicio 6 (Archivo: ejercicio.html)
1. Abrir el archivo `ejercicio.html` en un navegador web.
2. Esperar a que la página cargue y muestre "Listo. Sube una imagen.".
3. Seleccionar una imagen de un animal.
4. Hacer clic en "Clasificar y buscar descripción".
5. La web utiliza MobileNet para clasificar la imagen y consulta la API gratuita de Wikipedia para mostrar la descripción del animal.

## Notas generales
- No es necesario incluir `node_modules` ni librerías extra.
- `index.html` es el frontend para el ejercicio 5 y requiere el backend `sistema.js` en el puerto `8008`.
- `ejercicio.html` es independiente y puede abrirse directamente en el navegador.