```mermaid
 graph TD;
    A[Start] --> B[Investigación de tecnologías diseñadas para la captación de señales encefálicas];
    B --> C[Investigación de hardware y sensores relacionados];
    C --> D[Diseño de la placa de circuito impreso en EAGLE];
    D --> E[Adquisición de componentes pendientes];
    E --> F[Diseño y fabricación del PCB];
    F --> G[Colocacion y soldadura de componentes en PCB];
    G --> H[Etapa inicial: recoleccion y analisis de datos de actividades cerebrales];
    H --> I[Procesamiento de señales y evaluación con algoritmos de predicción];
    I --> J{¿Resultados satisfactorios?};
    J -- No --> K[Ajustes en algoritmos, consulta con el asesor y correcciones];
    J -- Sí --> L[Optimización del modelo de predicción y nuevas pruebas];
    K --> L;
    L --> M[Ajustes finales y detalles de presentación];
    M --> N[Preparación y exposición del proyecto con su documentación];
    N --> O[Finalizacion del proyecto con su documentación];
    O --> P[Completed];
