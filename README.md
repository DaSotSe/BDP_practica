## Estructura del Proyecto y Localización de Archivos Practica David Sotelo Seguín

Este repositorio contiene los ejercicios prácticos desarrollados con Apache Spark en Scala. A continuación, se describe la estructura principal del proyecto para facilitar la navegación y revisión del código y sus pruebas.

src/
├── main/
│   └── scala/
│       └── sesion4/
│           ├── Sesion4.scala         # Código principal en Spark
│                        
│
├── test/
│   ├── resources/
│   │   ├── calificaciones.csv        # Dataset de ejemplo para pruebas
│   │   ├── estudiantes.csv
│   │   ├── operaciones.csv
│   │   └── ventas.csv                # Dataset usado en los tests (distinto del ubicado en main)
│   └── scala/
│       └── sesion4/
│           └── Sesion4Test.scala     # Archivo de test para validar el código

### 📄 Archivos clave

- `Sesion4.scala`: contiene el desarrollo del ejercicio.
- `Sesion4Test.scala`: pruebas unitarias asociadas al código principal.
- **Datasets para pruebas:** ubicados en `src/test/resources/`, se utilizan en los tests para validar las transformaciones.
