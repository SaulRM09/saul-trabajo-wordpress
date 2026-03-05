# Publicación de la página web con InfinityFree

Para publicar la página web creada en local, se utilizó el servicio de hosting gratuito **InfinityFree**, que permite subir archivos HTML, CSS, JavaScript e imágenes para que la web sea accesible desde Internet. A continuación se detalla el proceso completo seguido para subir el proyecto desde la máquina local al servidor.

---

## Creación de la cuenta en InfinityFree
InfinityFree ofrece alojamiento gratuito sin anuncios obligatorios y con soporte para páginas estáticas y dinámicas.

### Pasos realizados:
1. Acceder a la web oficial: **https://infinityfree.net**
2. Crear una cuenta con correo electrónico y contraseña.
3. Confirmar la cuenta desde el correo recibido.
4. Acceder al panel de control de InfinityFree.

---

## Creación del hosting
Una vez dentro del panel, se creó un nuevo hosting gratuito para alojar la página.

### Pasos realizados:
1. Entrar en la sección **Accounts**.
2. Pulsar **Create Account**.
3. Elegir un subdominio gratuito del tipo:
   ```
   nombreproyecto.infinityfreeapp.com
   ```
4. Esperar a que InfinityFree configure el hosting.
5. Acceder al panel del hosting creado.

El directorio donde deben subirse los archivos es:

```
/htdocs
```

---

## Subida de los archivos desde la máquina local
Para publicar la página, se subieron los archivos del proyecto (HTML, CSS, JS, imágenes, etc.) al servidor.

### Método utilizado: File Manager
1. En el panel del hosting, abrir **File Manager**.
2. Entrar en la carpeta **htdocs**.
3. Eliminar el archivo por defecto **index2.html**.
4. Subir los archivos del proyecto local:
   - `index.html` (archivo principal)
   - Carpetas como `/css`, `/js`, `/img`, etc.
5. Comprobar que todos los archivos se han subido correctamente.

---

## Importante a tener en cuenta
Al subir la web desde local a InfinityFree, **no todo funcionará exactamente igual** que en tu entorno local. Es importante saber que:

- Los **plugins de WordPress no se importan** simplemente subiendo archivos HTML.  
- Los **anuncios creados con Ad Inserter** no aparecerán si no se está usando WordPress en el hosting.  
- Los **scripts avanzados** pueden no ejecutarse por restricciones del hosting gratuito.  
- Algunas funciones dinámicas pueden requerir **PHP, base de datos o configuración adicional**.  
- InfinityFree bloquea ciertos tipos de código por motivos de seguridad.

Esto significa que la versión publicada será una **versión estática** de tu proyecto, y algunos elementos avanzados no estarán disponibles.

---

## Visualización de la página publicada
Una vez subidos los archivos, la página quedó disponible públicamente en la URL asignada por InfinityFree:

```
https://nombreproyecto.infinityfreeapp.com
```

Si el archivo principal se llama **index.html**, se mostrará automáticamente al acceder al dominio.

---

## Consideraciones importantes
- El archivo principal debe llamarse **index.html** o **index.php**.
- Las rutas deben ser relativas para evitar errores al subir la web.
- InfinityFree no permite algunos scripts por motivos de seguridad.
- Si se actualiza la web, basta con reemplazar los archivos en **htdocs**.



### Imágenes de la web publicada: 
![Wordpress](https://github.com/SaulRM09/saul-trabajo-wordpress/blob/main/Imagenes/Imagen26.png)
![Wordpress](https://github.com/SaulRM09/saul-trabajo-wordpress/blob/main/Imagenes/Imagen27.png)

 
