# RS GPS Racing Labs Beta 2.3 — Quality Engine
Aplicación web independiente, sin backend. Publicar index.html por HTTPS para probar GPS en Android Chrome.

Cambios:
- Panel de diagnóstico: precisión declarada, frecuencia media aproximada de las últimas muestras, intervalo más reciente y rechazos.
- Rechazo de muestras atrasadas/duplicadas, calidad máxima 15 m para aceptar.
- No se interpolan tiempos de parciales atravesados en intervalos de más de 1,5 s; quedan ausentes, no inventados.
- Metadatos de calidad guardados con tiradas reales.
- Se conservan cinco tiradas DEMO separadas, diez puntos por curva, diseño RS, historial y comparaciones.

Limitaciones: sin validación de pista física, navegador puede detener el GPS en segundo plano. GPS de teléfono no garantiza precisión oficial. Las coordenadas quedan en la memoria durante la tirada y los registros locales contienen distancia, tiempo, velocidad y precisión; no se suben a servidor.
