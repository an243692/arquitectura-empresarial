# Arquitectura Empresarial - Documentacion

## Estructura del Repositorio (Trunk-Based Development)

### Trunk (main)
La rama principal `main` representa la linea de desarrollo estable.

### Branches (Ramas de Caracteristicas)
- `feature/servicios-web` - Desarrollo de servicios web REST
- - `feature/integracion` - Modulo de integracion
 
  - ### Tags (Versiones)
  - - `v1.0.0` - Primera version estable
    - - `v1.1.0` - Mejoras de rendimiento
     
      - ## Servicios Web
     
      - ### REST vs SOAP
      - Este proyecto implementa una API REST por las siguientes razones:
      - - **Interoperabilidad**: Compatible con cualquier cliente HTTP
        - - **Rendimiento**: Menor overhead que SOAP
          - - **Simplicidad**: Formato JSON mas ligero que XML
           
            - ## Ciclo de Trabajo Git
           
            - 1. git clone - Copia de trabajo local
              2. 2. git pull - Actualizacion de copia
                 3. 3. git add + git commit - Registrar cambios
                    4. 4. Pull Request - Fusionar cambios colaborativamente
                       5. 
