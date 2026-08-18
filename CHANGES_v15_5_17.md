# PhysioSentinel AI v15.5.17

## Corrección exclusiva: ángulo de fechas en pestaña 3 · Comparar

Parte de v15.5.16 y mantiene intacto todo lo demás.

### Cambio
En el dashboard evolutivo de la pestaña 3) Comparar:
- las etiquetas de fecha/hora del eje X pasan de 0° a -45°;
- se activa `automargin=True`;
- se amplía ligeramente el margen inferior para evitar recortes.

Se aplica en:
- comparación de un paciente;
- comparación multipaciente;
- una fase;
- varias fases.

El comportamiento replica el criterio visual ya usado en la pestaña 9) Índices fisiológicos.

### Sin otros cambios
No se modifican cálculos, métricas, gráficos restantes, animación de atractores,
exportación MP4/GIF, Control autonómico, XGBoost, calibración ni predicción.
