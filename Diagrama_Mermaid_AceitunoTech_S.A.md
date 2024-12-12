```mermaid
flowchart TD
    A[Nombre de la Empresa: AceitunoTech S.A.]

    %% Sector and Description Group
    subgraph Sector y Descripción
        A --> B[Sector: Agricultura y tecnología]
        A --> C[Descripción]
        C --> C1[Especializada en aceitunas y productos derivados]
        C --> C2[Estrategia: Incrementar competitividad local e internacional]
    end

    %% Tamaño
    A --> D[Tamaño: 200 empleados]

    %% Products Group
    subgraph Productos
        A --> E[Productos]
        E --> E1[Frutas frescas: Manzanas, Naranjas, Aceitunas]
        E --> E2[Verduras frescas: Lechuga, Zanahorias]
        E --> E3[Derivados: Jugos naturales, Conservas de aceitunas]
    end

    %% Clients Group
    subgraph Clientes
        A --> F[Clientes]
        F --> F1[Supermercados]
        F --> F2[Restaurantes y mayoristas]
        F --> F3[Exportadores a Europa y Norteamérica]
    end

    %% Current Challenges Group
    subgraph Desafíos Actuales
        A --> G[Desafíos actuales]
        G --> G1[Uso eficiente de recursos: Agua, energía, fertilizantes]
        G --> G2[Logística: Mejorar entregas e inventarios]
        G --> G3[Satisfacción de demanda: Producción sostenible]
        G --> G4[Desafíos tecnológicos: IA, IoT, Big Data]
    end

    %% Production Technologies Group
    subgraph Tecnologías para Producción
        A --> H[Tecnologías para mejorar la producción]
        H --> H1[Sensores IoT: Monitoreo de cultivos]
        H1 --> H1a[Miden humedad, temperatura, radiación solar]
        H1 --> H1b[Optimizan agua y fertilizantes]
        H --> H2[Drones: Supervisión de campos]
        H2 --> H2a[Detectan plagas y problemas]
        H2 --> H2b[Previenen pérdidas]
        H --> H3[Mantenimiento predictivo con IA]
        H3 --> H3a[Analiza datos de maquinaria]
        H3 --> H3b[Evita paradas imprevistas]
    end

    %% Administration Technologies Group
    subgraph Tecnologías para Administración
        A --> I[Tecnologías para mejorar la administración]
        I --> I1[Sistemas ERP: Inventarios, logística y recursos]
        I1 --> I1a[Mejor planificación y toma de decisiones]
        I --> I2[Chatbots: Atención al cliente]
        I2 --> I2a[Responden preguntas automáticamente]
        I2 --> I2b[Mejoran la experiencia del cliente]
    end

    %% AI Impact Group
    subgraph Impacto de la IA
        A --> J[Impacto de la IA en el sector agrícola]
        J --> J1[Actual: Optimización de cultivos, reducción de costos]
        J --> J2[Futuro: Gestión más eficiente y sostenible]
        J2 --> J2a[Drones autónomos y sensores avanzados]
    end
