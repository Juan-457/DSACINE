# DSACINE

Sitio web estatico de DSACINE / Donde Sucede el Arte, orientado a promocionar clases, docentes, casting y contacto para la academia.

## Contenido

- `index.html`: home principal.
- `nosotros.html`, `profesores.html`, `contacto.html`: paginas institucionales.
- `casting.html` y `faq.html`: secciones enlazadas desde la navegacion del sitio.
- `productor.mp4`, `fondo.png`, `logo.jpg`: assets principales del hero y marca.
- `CNAME`: dominio personalizado.

## Stack

- HTML estatico
- CSS embebido
- JavaScript vanilla para interacciones basicas
- Assets locales para logo, video e imagenes

No requiere dependencias ni build.

## Verlo localmente

```bash
cd DSACINE
python3 -m http.server 8000
```

Abrir `http://localhost:8000`.

## Deploy

Sitio listo para publicarse como hosting estatico. Si se usa GitHub Pages o un proveedor similar:

- publicar la raiz del repo
- conservar `CNAME`
- revisar que todas las paginas auxiliares enlazadas existan en produccion

## Notas

- El sitio ya incluye estructura de navegacion entre home, casting, profesores, preguntas frecuentes y contacto.
- Si se suman nuevas paginas, mantener la consistencia de enlaces en desktop y mobile.
