```mermaid
graph TD
    A[Presidencia Ejecutiva] --> B[Consejo Directivo]
    B --> C[Dirección General]

    %% Órganos de línea
    C --> D1[Gerencia Administrativa]
    C --> D2[Gerencia de Producción]
    C --> D3[Gerencia de Ventas]
    
    %% Asesorías externas y comités (líneas discontinuas simuladas)
    C -->|--->| E1[Asesoría Legal Externa]
    C -->|--->| E2[Comité Técnico Externo]

    %% Sectores de apoyo en proyecto
    C -->|...>| F1[Departamento de Innovación (En Proyecto)]
    C -->|...>| F2[Unidad de Transformación Digital (En Proyecto)]
