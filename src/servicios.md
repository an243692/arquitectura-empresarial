# Modulo de Servicios Web - REST

## Endpoints Definidos
- GET /api/productos - Lista de productos
- - POST /api/productos - Crear producto
  - - PUT /api/productos/{id} - Actualizar producto
    - - DELETE /api/productos/{id} - Eliminar producto
     
      - ## Ventajas REST
      - 1. Menor consumo de ancho de banda (JSON vs XML)
        2. 2. Mayor compatibilidad con navegadores modernos
           3. 3. Facilidad de integracion con frameworks frontend
             
              4. ## Formato de Respuesta JSON
              5. {
              6.   "status": "success",
              7.     "data": {},
              8.   "message": "Operacion exitosa"
              9.   }
              10.   
