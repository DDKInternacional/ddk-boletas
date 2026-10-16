# DDK · Boletas de Seguridad e Incidencias

Página estática (un solo `index.html`, sin servidor ni base de datos) que usan los oficiales de DDK Internacional Seguridad para generar boletas y enviarlas por WhatsApp. Los datos (consecutivo, historial) se guardan únicamente en el celular que la usa.

Tipos de boleta: **Control vehicular**, **Mascotas**, **Ruido y convivencia**, **Áreas comunes y propiedad**, **Personas y accesos** y **Otra incidencia**. Cada tipo tiene su propia lista de situaciones reportadas, nivel de gravedad, acción tomada y fotos de evidencia.

## Publicación en Render (sitio estático)

Servicio `ddk-boletas` en Render conectado a este repositorio. Branch: `main` · Build command: *(vacío)* · Publish directory: `.` → https://ddk-boletas.onrender.com

Cada cambio que se suba a `main` se publica solo.

## Instalación en los celulares

1. Abrir el enlace en **Safari** (iPhone) o **Google Chrome** (Android).
2. Compartir → **Agregar a pantalla de inicio**. Queda como una app con el ícono de DDK.
3. Abrirla desde el ícono, tocar ⚙️, ingresar el PIN y asignar la **letra del celular** (A, B, C…).

> El archivo HTML **no funciona** si se abre desde la vista previa de WhatsApp, correo o Archivos (iOS bloquea los scripts ahí). Siempre debe abrirse desde el enlace.
