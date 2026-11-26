# ⛽ Stock Shell — App de stock y ventas

App interactiva para el teléfono: control de stock, ventas en pesos, Mercado Pago y combustible, en un solo archivo (`index.html`). Funciona **sin internet** y guarda todo solo en el teléfono.

## Cómo usarla en el teléfono

1. Abrí el archivo `index.html` en el navegador (Chrome) del celular.
2. Menú del navegador → **"Agregar a pantalla de inicio"** → queda como una app más.

> Para tenerla siempre con una dirección fija: en GitHub, entrá a **Settings → Pages**, elegí *Deploy from a branch*, rama `main`, carpeta `/ (root)` y guardá. En un minuto la app queda en `https://nicoolasurqui58.github.io/Stock-shell/` y desde ahí la agregás a la pantalla de inicio.

## Qué tiene

- **📦 Stock**: tocá **+** o **−** para sumar o restar unidades de un toque. Tocá el nombre para editar producto, cantidad o precio.
- **🛒 Ventas**: cargás producto (o escribís uno libre), cantidad y precio → se suma solo al total del día en pesos. Elegís si se cobra en efectivo o Mercado Pago. Si el producto existe en el stock, se descuenta automáticamente.
- **⛽ Combustible**: precios por litro editables (Súper, Premium, Diésel), registrás litros vendidos y calcula el total.
- **💰 Resumen**: totales del día (efectivo / MP con comisión / combustible), valor total del stock, exportar a CSV, copia de seguridad JSON, historial de días cerrados.

## Datos

Todo se guarda en el navegador del teléfono (localStorage). Ojo: si borrás los datos del navegador, se borra la app. Sacá una **Copia JSON** de vez en cuando desde Resumen.
