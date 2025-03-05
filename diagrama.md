graph TD;
    A[Inicio] --> B[Recepción y almacenamiento de insumos] --> C[¿Insumos en buen estado?]
    C -- Sí --> D[Mezcla de ingredientes] --> E[Formación de cubos de hielo] --> F[¿Calidad adecuada?]
    F -- Sí --> G[Empaque] --> H[¿Empaque sellado?] --> I[Almacenamiento] --> J[Distribución] --> K[Fin]
    C -- No --> B
    F -- No --> E
    H -- No --> G
