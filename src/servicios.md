# Modulo de Servicios Web

## Decision: REST seleccionado tras analisis comparativo

## Comparativa REST vs SOAP

| Caracteristica | REST | SOAP |
|---|---|---|
| Formato | JSON | XML |
| Rendimiento | Alto | Medio |
| Complejidad | Baja | Alta |

## Endpoints REST Implementados
- GET /api/productos - Lista de productos
- - POST /api/productos - Crear producto
- - PUT /api/productos/{id} - Actualizar producto
- - DELETE /api/productos/{id} - Eliminar producto

## Conclusion
Se selecciona REST por mayor rendimiento e interoperabilidad en la arquitectura empresarial.
