graph TD;
    A(Inicio) --> B(Recepción de mercancías);
    B --> C{¿Cantidad y calidad correctas?};
    C -->|Sí| D(Almacenamiento);
    C -->|No| E(Comunicar al proveedor);
    D --> F(Gestión de inventarios);
    E --> F;
    F --> G(Registro en el sistema);
    G --> H(¡Fin!);
