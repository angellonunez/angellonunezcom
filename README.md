# Blog personal - Angello Nunez

> 🧑‍🚀 **Creado con Astro**

Puedes ver la página web [aquí](https://angellonunez.com).

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── BaseHead.astro
│   │   └── Disqus.astro
│   │   └── FormattedDate.astro
│   │   └── Header.astro
│   │   └── HeaderLink.astro
│   ├── layouts/
│   │   └── BlogPost.astro
│   │   └── AboutLayout.astro
│   └── pages/
│       └── index.astro
│       └── about.astro
└── package.json
```

Astro busca archivos `.astro` o `.md` en la carpeta `src/pages/`. Cada página es mostrada como una ruta basada en el nombre del archivo.

No hay nada especial en `src/components/`,pero allí es donde prefiero guardar los componentes de Astro/React/Vue/Svelte/Preact.

Cualquier recurso estático, como imágnes, pueden ser puestas en la carpeta `public/`.

## 🧞 Comandos

Todos los comandos se corren desde la raíz del proyecto, a través de una terminal:

| Comando                   | Acción                                                            |
| :------------------------ | :---------------------------------------------------------------- |
| `npm install`             | Instala dependencias                                              |
| `npm run dev`             | Empieza un servidor local de desarrollo en `localhost:4321`       |
| `npm run build`           | Contruye tu sitio de producción en `./dist/`                      |
| `npm run preview`         | Visualiza tu producción localmente, antes de lanzar públicamente  |
| `npm run astro ...`       | Corre comandos CLI como `astro add`, `astro check`                |
| `npm run astro -- --help` | Consigue ayuda corriendo el Astro CLI                             |

## 👀 ¿Quieres aprender más de Astro?

Siéntete libre de revisar [su documentación](https://docs.astro.build) o visitar su [servidor de Discord](https://astro.build/chat).
