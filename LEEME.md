# Sitio Cabaña Amakaik — instrucciones de carga

## Repositorio
jjdastolfo-ui / PaginaAmakaik — rama `main`

## Estructura final

    PaginaAmakaik/
    ├── index.html            <- reemplaza al que esta subido
    ├── padres.html           <- nuevo
    ├── toro-hercules.html    <- nuevo
    ├── toro-zeus-ii.html     <- nuevo
    ├── img/
    │   ├── logo-amakaik.png
    │   ├── DJI_0089.webp     (portada)
    │   ├── DJI_0087.webp
    │   ├── IMG_1744.webp
    │   └── ... (el resto de la galeria, ya estan subidas)
    │   └── toros/            <- CARPETA NUEVA, falta crearla
    │       ├── hercules-1.webp  hercules-2.webp  hercules-3.webp  hercules-4.webp
    │       └── zeus-ii-1.webp   zeus-ii-2.webp   zeus-ii-3.webp   zeus-ii-4.webp
    └── catalogos/
        ├── toros-pp-2026.pdf     (ya subido)
        ├── vaquillonas-2026.pdf  <- falta
        └── catalogo-2023.pdf     <- falta

## Como subir los HTML

1. Entra al repo en GitHub.
2. Add file -> Upload files.
3. Arrastra los cuatro HTML juntos.
4. Commit changes. Reemplaza index.html sin problema.

## Como subir las fotos de los toros

GitHub no deja crear una carpeta vacia. Se crea sola al subir el primer archivo:

1. Add file -> Upload files.
2. Antes de arrastrar nada, en el campo de la ruta escribi:  img/toros/
3. Arrasta las 8 fotos ahi.
4. Commit changes.

Los nombres tienen que ser exactos, en minuscula:
hercules-1.webp a hercules-4.webp, zeus-ii-1.webp a zeus-ii-4.webp

Si las fotos son .jpg en vez de .webp, avisame y cambio la extension en los HTML.
No hace falta que sean cuatro: si tenes dos, subi esas dos y saco las miniaturas de mas.

## Verificar

https://jjdastolfo-ui.github.io/PaginaAmakaik/

Tarda uno o dos minutos en actualizarse despues de cada commit.

## Todavia pendiente

- Tabla E.R.A. de Zeus II (el PDF vino con una columna corrida)
- Datos productivos de los dos toros: peso actual, GDP, circ. escrotal medida
- Los dos catalogos PDF que faltan
- El resto de los toros padres
