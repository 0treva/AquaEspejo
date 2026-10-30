# AquaEspejo

Web estática en español para limpieza de cisternas, aljibes y tinacos en Guadalajara. HTML, CSS y JavaScript, sin instalación ni compilación. Incluye precios informados por el negocio, fotografías reales, preguntas frecuentes y enlaces directos a WhatsApp. No hay formulario.

## Archivos

- `index.html`: estructura y textos.
- `styles.css`: diseño adaptable a móvil y escritorio.
- `script.js`: año del pie de página.
- `assets/`: anuncio y tres fotografías seleccionadas, además de un símbolo provisional.
- `docs/PLAN-REDES.md`: estrategia, calendario de cuatro semanas, 12 textos, respuestas y seguimiento comercial.

## Vista local

Desde esta carpeta:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Abrir http://127.0.0.1:8000. Para terminar el servidor, Ctrl+C.

## GitHub Pages

1. Crear o elegir un repositorio en GitHub.
2. Subir `index.html`, `styles.css`, `script.js`, `.nojekyll` y la carpeta `assets` a la raíz de la rama `main`. El ZIP `aquaespejo-web.zip` contiene solo estos archivos.
3. En el repositorio abrir **Settings → Pages**.
4. Elegir **Deploy from a branch**, rama `main`, carpeta `/ (root)` y guardar.
5. Esperar a que GitHub muestre la URL publicada y comprobar enlaces, imágenes y versión móvil.

Los enlaces a archivos son relativos, por lo que sirven en una URL de proyecto como `https://USUARIO.github.io/REPOSITORIO/`. Consultar la [documentación oficial de GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) para disponibilidad y configuración.

## Datos y cambios

Precios: cisterna/aljibe $3,200; tinaco $1,000; ambos $4,000 MXN. El ahorro aritmético del paquete es $200. Confirmar límites de capacidad, impuestos y alcance antes de lanzar.

El WhatsApp `523326371532` proviene del anuncio proporcionado. Todos los enlaces contienen exactamente este mensaje:

> Hola, vi la pagina web de Aqua Espejo y quiero cotizar el servicio de limpieza de cisternas 💧

Para cambiar número o mensaje, actualizar todos los enlaces `https://wa.me/` en `index.html`. El texto de la URL está codificado; no hace falta un backend.

Las fuentes se solicitan a Google Fonts; si no hay conexión se usan fuentes del sistema. No se añadieron analítica, píxeles publicitarios ni cookies propias. GitHub y WhatsApp operan sus propios servicios. La web no garantiza potabilidad ni publica testimonios o certificaciones no aportados.

El anuncio conserva la marca original. El símbolo de gota y la ilustración de cisterna son elementos provisionales de diseño; sustituir el símbolo por el logotipo original cuando se proporcione por separado.

Las tres fotos se copiaron de Fotos sin alterar originales. No se afirma que constituyan una secuencia antes/después. Videos y ZIP originales no forman parte del sitio. No subir la carpeta Fotos completa ni documentos internos al repositorio público.

Metadatos configurados para la dirección prevista `https://0treva.github.io/AquaEspejo/`, según el repositorio indicado. La publicación aún requiere acceso a GitHub. Pendientes: redes reales, cobertura y horarios. No se han creado cuentas ni publicado en redes.
