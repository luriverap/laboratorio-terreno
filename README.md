# Laboratorio de terreno e índices

Laboratorio interactivo del curso **Geomática** · Ingeniería Agronómica · Universidad EAFIT · 2026‑2.

**Abrir el laboratorio:** https://luriverap.github.io/laboratorio-terreno/

Funciona en cualquier navegador y no hay que instalar nada. La imagen satelital y el modelo de elevación vienen incluidos en la página.

## Qué se practica

Siete misiones sobre un recorte real de 9 × 6 km en Venecia (Antioquia), sector de Bolombolo.

| # | Misión | Qué se hace |
|---|---|---|
| 1 | Pendiente | Calcular la pendiente con la ventana de 3 × 3 celdas, pasar de grados a porcentaje y leer las clases del IGAC |
| 2 | Aspecto y sombreado | Ver hacia dónde mira cada ladera y mover el sol del sombreado |
| 3 | Álgebra de mapas | Escribir expresiones en una calculadora ráster con la sintaxis de QGIS y resolver cuatro retos |
| 4 | Índices | Calcular NDVI, NDWI, NDMI y EVI y compararlos en cinco puntos |
| 5 | Lotes y decisión | Correr estadísticas de zona sobre cinco lotes y decidir cuál renovar |
| 6 | Repaso | Diez preguntas de autoevaluación |
| 7 | Cuencas (complemento) | Soltar una gota, ver su recorrido y delimitar una cuenca |

## Insumos para QGIS

[`insumos_sesion13.zip`](insumos_sesion13.zip) trae los mismos datos de la página, en EPSG:9377: bandas B02, B03, B04, B08 y B11 (reflectancia, 10 m), el MDE de 30 m y los cinco lotes de práctica. Las cifras que obtengan en QGIS deben coincidir con las de la página.

## Datos

- **Imagen:** Sentinel‑2C, nivel L2A, 17 de septiembre de 2026, tesela 18NVM. Contiene datos modificados de Copernicus Sentinel (2026).
- **Elevación:** Copernicus DEM GLO‑30. © DLR e.V. 2010‑2014 y © Airbus Defence and Space GmbH 2014‑2018, provisto bajo COPERNICUS por la Unión Europea y la ESA.
- **Lotes:** polígonos de práctica, no son predios reales.

## Autoría y licencia

Luna Rivera Patiño, docente de Geomática, Universidad EAFIT.

Este material se comparte bajo la licencia [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.es): puede usarlo y adaptarlo, también en sus clases, citando a la autora. Los datos Copernicus conservan sus propios términos de uso. Más detalles en [LICENSE](LICENSE).
