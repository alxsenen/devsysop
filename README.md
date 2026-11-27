# devsysop.com

Sitio web de DevSysOp. HTML y CSS puros: no hay que instalar ni compilar nada.

## Estructura

```
index.html            Página principal
styles.css            Estilos
favicon.svg / .ico    Ícono de la pestaña
apple-touch-icon.png  Ícono para iPhone
assets/               Logos e imagen para compartir en redes
CNAME                 Dominio para GitHub Pages (no borrar)
```

## Ver el sitio en tu computadora

```bash
python3 -m http.server 8000
# abrir http://localhost:8000
```

## Publicar

El sitio se publica con GitHub Pages desde la rama `main` (carpeta raíz).
Cada `git push` a `main` actualiza devsysop.com en uno o dos minutos.

Si alguna vez deja de funcionar, revisá en GitHub: **Settings → Pages**
- Source: **Deploy from a branch** → `main` / `(root)`
- Custom domain: `devsysop.com`, con **Enforce HTTPS** marcado

El archivo `CNAME` tiene que quedar en el repo: es el que le dice a GitHub qué dominio usar.

## Precios

Los precios en pesos uruguayos se calcularon a 1 USD = 40 UYU. Si el dólar se mueve mucho, actualizalos en `index.html`.

## Pendientes antes de publicar

Buscá `[` en `index.html` para encontrar todo lo que falta completar:

- Nombres, fotos y experiencia
- Caso real y testimonio
- Forma de pago
- Link de Cal.com/Calendly, número de WhatsApp, email
- Links de LinkedIn y GitHub
