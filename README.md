flowchart TD
    A[Administrador - Dashboard] --> B[Cartas de Inicio]
    A --> C[Cartas de Fin]
    A --> D[Búsqueda Global de Alumnos]

    %% Cartas de Inicio
    B --> B1[Filtros<br>• Fecha<br>• Alumno<br>• Carrera]
    B --> B2[Lista de Cartas de Inicio]
    B2 --> B2a[Ver Carta]
    B2 --> B2b[Firmar Carta]
    B2 --> B2c[Descargar PDF]
    B --> B3[Detalles de Alumno]
    B3 --> B3a[Carta de Inicio]
    B3 --> B3b[Evidencias Subidas]

    %% Cartas de Fin
    C --> C1[Filtros<br>• Fecha<br>• Alumno<br>• Carrera]
    C --> C2[Lista de Cartas de Fin]
    C2 --> C2a[Ver Carta]
    C2 --> C2b[Firmar Carta]
    C2 --> C2c[Descargar PDF]
    C --> C3[Detalles de Alumno]
    C3 --> C3a[Carta de Fin]
    C3 --> C3b[Evidencias Subidas]

    %% Búsqueda
    D --> D1[Resultados]
    D1 --> D1a[Perfil del Alumno]
    D1a --> D1b[Carta de Inicio]
    D1a --> D1c[Carta de Fin]
    D1a --> D1d[Evidencias]

