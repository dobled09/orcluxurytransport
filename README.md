# OrcLuxuryTransport — Sitio web

Sitio web de una página para **OrcLuxuryTransport**, servicio de transporte turístico
y ejecutivo en Panamá.

## Ver el sitio

- **En línea:** https://dobled09.github.io/orcluxurytransport/
- **En local:** abrir `index.html` con doble clic. No requiere servidor ni conexión.

## Cómo está hecho

Un único archivo `index.html` que contiene todo: estructura, estilos (`<style>`) y
comportamiento (`<script>`). Sin frameworks ni librerías externas — solo HTML5, CSS3
y JavaScript puro.

Secciones: portada, quiénes somos, servicios, por qué elegirnos, galería con visor de
imágenes, testimonios y formulario de reserva.

## Reservas

El formulario no envía correos ni necesita servidor. Valida los datos, arma un mensaje
ordenado y abre WhatsApp con la solicitud lista para enviar. El número se configura en
la constante `CONFIG.whatsapp`, al inicio del `<script>`.

## Pendiente antes de la publicación final

- [ ] Reemplazar los espacios reservados por las fotografías reales de la flota
      (buscar `REEMPLAZAR FOTO` en el archivo).
- [ ] Reemplazar los testimonios de muestra por opiniones reales de clientes, y quitar
      las etiquetas "Texto de ejemplo" (`.marca-ejemplo`) y las notas `.nota-preview`.
- [ ] Conectar el dominio `orcluxurytransport.com`.

Las instrucciones detalladas de edición están comentadas al inicio de `index.html`.
