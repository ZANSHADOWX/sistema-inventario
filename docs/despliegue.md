# Estrategia de Despliegue

## Estrategia seleccionada: Blue/Green

### Justificación
El Sistema de Control de Inventario es crítico para la empresa. Blue/Green permite desplegar sin interrumpir el servicio y con rollback inmediato.

### Tabla de análisis

| Elemento | Descripción |
|----------|-------------|
| Estrategia | Blue/Green |
| Ambiente | Desarrollo / Pruebas / Producción |
| Proceso | Dos entornos idénticos; se despliega en Green y se cambia el tráfico |
| Riesgos | Costo de duplicar infraestructura |
| Ventajas | Cero downtime, rollback inmediato |
| Plan de recuperación | Redirigir tráfico a Blue si falla Green |
