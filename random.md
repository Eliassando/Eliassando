```mermaid
graph TD;
    A[Inicio] --> B[Recepción y almacenamiento de insumos];
    B --> C[¿Insumos en buen estado?];
    C -- Sí --> D[Mezcla de ingredientes];
    C -- No --> C1[Revisión de insumos] --> B;
    D --> E[Formación de cubos de hielo];
    E --> F[¿Calidad adecuada?];
    F -- Sí --> G[Empaque];
    F -- No --> F1[Ajuste de parámetros ] --> E;
    G --> H[¿Empaque sellado correctamente?];
    H -- Sí --> I[Almacenamiento en cámaras frigoríficas];
    H -- No --> H1[Corrección de empaque] --> G;
    I --> J[Distribución ];
    J --> K[Fin];
