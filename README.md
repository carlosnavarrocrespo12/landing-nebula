# Práctica: Landing Page de Nébula

Esta es mi entrega para la práctica de la página web de la artista digital "Nébula". He organizado las carpetas como se pedía en el enunciado dentro de assets/ (img, audio y video).

## 1. Tabla de Recursos y Licencias

| Archivo | Descripción | Enlace original | Licencia |
| :--- | :--- | :--- | :--- |
| logo.svg | Icono de un planeta para el logo | Hecho por mí | Dominio Público (CC0) |
| hero.webp | Imagen grande principal (1920px) | Pegar enlace aquí | CC BY 4.0 |
| thumb1.webp | Miniatura 1 de la galería (400x250) | Pegar enlace aquí | CC BY 4.0 |
| thumb2.webp | Miniatura 2 de la galería (400x250) | Pegar enlace aquí | CC BY 4.0 |
| thumb3.webp | Miniatura 3 de la galería (400x250) | Pegar enlace aquí | CC0 Dominio Público |
| cta.webp | Animación de botón de contacto | Hecho por mí con 3 imágenes | CC BY 4.0 |
| presentacion.mp4 | Vídeo corto del espacio | Pegar enlace aquí | CC0 Dominio Público |
| poster.webp | Captura sacada del vídeo | Propia (del vídeo anterior) | CC0 Dominio Público |
| ambiente.mp3 | Sonido espacial de 15 segundos | Pegar enlace aquí | CC0 Dominio Público |

## 2. Justificación de los Formatos Elegidos

* **Imágenes (.webp en vez de .jpg o .png):** He pasado la imagen principal, el póster del vídeo y las 3 miniaturas al formato .webp porque comprime mucho mejor que el JPG sin que se vea borroso. Así la imagen principal de 1920px me ha quedado en menos de 250 KB y la página carga más rápido.
* **Logotipo (.svg):** He elegido .svg para el logo porque al ser un gráfico vectorial no se pixela nunca aunque hagas zoom en la pantalla. Además tiene el fondo transparente y no pesa casi nada (menos de 2 KB).
* **Animación (.webp animado en vez de .gif):** He exportado la animación de las 3 imágenes en .webp animado porque pesa bastante menos que el .gif tradicional y permite mejores colores sin bordes pixelados.
* **Vídeo (.mp4):** He usado .mp4 porque es el formato que funciona en todos los navegadores sin dar problemas y permite comprimirlo fácil para que ocupe menos de los 3 MB que pedía la tarea.
* **Audio (.mp3):** He exportado el sonido en .mp3 a 128 kbps porque un archivo .wav ocuparía demasiado espacio para una web, mientras que el .mp3 se escucha bien y pesa muy poco para los 15 segundos que dura.

## 3. Herramientas que he utilizado

* **Squoosh y Ezgif:** Los he usado para cambiar el tamaño de la imagen principal a 1920px de ancho, recortar las 3 miniaturas a 400x250px y pasarlas a formato .webp bajando un poco la calidad para que pesen poco.
* **Ezgif.com:** Lo he utilizado para juntar las 3 imágenes fijas del botón de contacto y crear la animación en bucle en .webp.
* **HandBrake:** Lo he usado para bajarle el peso y el bitrate al vídeo descargado para que ocupe menos de 3 MB en .mp4.
* **AudioMass / Audacity:** Lo he usado para cortar el audio a 15 segundos exactos, ponerle el efecto de Fade-in al principio y Fade-out al final, y guardarlo en .mp3.