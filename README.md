
## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`             | Installs dependencies                            |
| `pnpm dev`             | Starts local dev server at `localhost:4321`      |
| `pnpm build`           | Build your production site to `./dist/`          |
| `pnpm preview`         | Preview your build locally, before deploying     |
| `pnpm astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `pnpm astro -- --help` | Get help using the Astro CLI                     |
| `pnpm run dev`         | Ejecutar el programa                             |




# CONSIDERACIONES
JAMAS DE LOS JAMACES le hagan cambios a la rama master, origin o dev.
Porque ya tuvimos problemas serios con eso y prefiero evitarlo.

Simpre hagan las cosas en su rama.

La version final sera la rama dev, donde esa sera la version del proyecto que se entrege
(no sera master o origin porque esa se usara como respaldo por si alguna cosa pasa)


La persona que se encargue de pasar los cambios de tu rama a la rama dev sera ariel, es para mantener el orden y evitar problemas de versiones porfavor

Avisame mandandome un mensaje o algo para que lo revise. Gracias

## Paso 1
Descargar node js

## Paso 2
Ejecutar el programa

```sh
pnpm run dev
```

## Paso 3
OBLIGATORIO:
Situarte en la rama dev, y crear una nueva rama con tu nombre.

Esto es para que no tengamos problemas de compatibilidad

```sh
git switch dev
```

```sh
git checkout -b nombre-de-tu-rama
```

## Paso 4
Subir los cambios a tu rama


```sh
git add .
```

```sh
git commit -m Nombre del commit
```


```sh
git push
```

## Paso 5
Obtener los cambios de la rama dev a tu rama
OJO: RECUERDA SUBIR TUS CAMBIOS ANTES DE HACER ESTO

```sh
git merge dev
```

## Paso 6
Para pasar los cambios de tu rama a la rama dev porfavor comentale a Ariel que ya terminaste los cambios y que ya esta listo para hacerlo

