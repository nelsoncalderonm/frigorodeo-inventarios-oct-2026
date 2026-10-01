# Inventario físico Frigorodeo · oct 2026

App web de un solo archivo (`index.html`, sin build) para el inventario cárnico y de insumos por punto de venta.

- Cárnico: pesaje con tara por tipo de canastilla (mediana 1,8 · grande 2,0 · base 1,5 · base de embutidos 1,25 kg).
- Insumos: conteo de nuevos / en uso.
- Inventarios por punto de venta + fecha, con encargado, hora de inicio y cierre.
- Vista consolidada de todos los puntos y exportación a CSV.
- Hoy los datos se guardan en el navegador (localStorage). El esquema de Supabase (`inv2026v3_*`) ya existe; falta conectar login y sincronización.
