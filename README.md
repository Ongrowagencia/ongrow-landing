# OnGrow — Landing Page

Landing page de OnGrow (agencia de e-commerce y digital marketing en Chile), pensada para recibir tráfico de campañas y convertir visitas en contactos por WhatsApp o formulario.

## Estructura

Sitio estático de una sola página (`index.html`), sin build ni dependencias. Se despliega tal cual en Vercel.

## Editar contenido

Todo el contenido, estilos y comportamiento están en `index.html`:
- Colores y tipografía: bloque `<style>` al inicio del archivo (variables CSS en `:root`)
- Textos: directamente en el HTML de cada sección
- WhatsApp: número configurado en la constante `WHATSAPP_NUMBER` dentro del `<script>` al final del archivo

## Desarrollo local

Abre `index.html` directamente en el navegador, o sirve la carpeta con cualquier servidor estático:

```bash
npx serve .
```

## Deploy

Conectado a Vercel mediante GitHub: cada `git push` a `main` genera un deploy automático.
