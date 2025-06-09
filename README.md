<div align="center">
<picture>
    <source srcset="https://imgur.com/5bYAzsb.png" media="(prefers-color-scheme: dark)">
    <source srcset="https://imgur.com/Os03JoE.png" media="(prefers-color-scheme: light)">
    <img src="https://imgur.com/Os03JoE.png" alt="Escudo UNAL" width="350px">
</picture>

<h3>AUTOMATIZACIÓN DE PROCESOS DE MANUFACTURA</h3>

<h1>Módulo 3 - Planeación de proyecto</h1>

<h2>Mep Mep Raideres</h2>

<h5>Joan Sebastian Arcila <br>
    Juan Sebastian Daleman Martinez<br>
    Daniel Santiago Muñoz Bernal<br>
    Maria Alejandra Pérez Petro<br>
    Emma Carolina Sarmiento Cabarcas</h5>

<h6>Universidad Nacional de Colombia<br>
    Facultad de Ingeniería<br>
    Departamento de Ingeniería Mecánica y Mecatrónica<br>
    Bogotá, Colombia<br>
    2025</h6>
</div>


<details>
    <summary>🗂️ Tabla de Contenido</summary>

<!-- TOC -->
- [EDT (Estructura de desgloce de trabajo)](#edt-estructura-de-desgloce-de-trabajo)


</details>

# EDT (Estructura de desgloce de trabajo)

 ```mermaid
flowchart RL
    A["Proyecto de Automatización de Ensamble de Patinetas"] --> B["1 Gestión del proyecto"] & C["2 Análisis de mercado y selección de productos"] & D["3 Diseño del Proceso de Ensamble"] & E["4 Planeación de rutina"] & F["5 Desarrollo del Sistema Automatizado"] & G["6 Evaluación Económica"] & H["7 Comunicaciones"] & I["8 Implementación Ladder"] & J["9 Diseño HMI y SCADA"] & K["10 Documentación y Entregables"]
    B --> B1["1.1 Revisión del reto del curso, objetivos y entregables"] & B2["1.2 Elaboración del EDT"] & B3["1.3 Creación del cronograma"] & B4["1.4 Designación de roles y responsabilidades por tarea"]
    C --> C1["2.1 Realizar estudio de mercado y definir objetivo de producción"] & C2["2.2 Selección de los tres modelos de patineta e identificación de características técnicas"] & C3["2.3 Comparación entre modelos"] & C4["2.4 Descomposición funcional y de ensamblaje"]
    D --> D1["3.1 Elaboración de VSM considerando el estado actual de la planta pre-automatización"] & D2["3.2 Elaboración propuesta de automatización y VSM post automatización"] & D3["3.3 Elaborar propuesta de layout general del proceso"] & D4["3.4 Realizar simulación para validar el layout"]
    E --> E1["4.1 Crear diagrama de flujo del proceso de la planta"] & E2["4.2 Diseñar rutina base en lenguaje grafcet"]
    F --> F1["5.1 Diseño de celda robotizada"] & F2["5.2 Selección de sensores, actuadores, PLCs y herramientas"] & F3["5.3 Elaboración del modelo virtual en NX"] & F4["5.4 Cálculo de los Indicadores de producción"]
    G --> G1["6.1 Estimación de costos operativos, de materiales, equipos e inversión necesaria"] & G2["6.2 Estimación de flujo de caja del proyecto"] & G3["6.3 Cálculo VPN, TIR, Payback, ROI"]
    H --> H1["7.1 Diseñar arquitectura de comunicaciones"] & H2["7.2 Crear servidor OPC"] & H3["7.3 Probar comunicaciones en NX-Studio5000"]
    I --> I1["8.1 Traducir Grafcet a Ladder"] & I2["8.2 Crear rutinas en NX-Studio5000"] & I3["8.3 Simular en el entorno NX"]
    J --> J1["9.1 Configurar el cliente y servidor de OPC"] & J2["9.2 Diseñar la interfaz gráfica"] & J3["9.3 Probar la interfaz en tiempo real junto con el gemelo digital"]
    K --> K1["10.1 Redacción de informe técnico"] & K2["10.2 Presentación del sistema y simulación en clase"] & K3["10.3 Elaboración sitio web"]

    A@{ shape: hex}
    B@{ shape: hex}
    C@{ shape: hex}
    D@{ shape: hex}
    E@{ shape: hex}
    F@{ shape: hex}
    G@{ shape: hex}
    H@{ shape: hex}
    I@{ shape: hex}
    J@{ shape: hex}
    K@{ shape: hex}
```

