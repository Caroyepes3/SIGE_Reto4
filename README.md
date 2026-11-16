# ⚡ SIGE – Sistema de Gestión Energética
## Reto 4 – Panel de supervisión y control de una MicroRed

### 1. Descripción del proyecto

SIGE es una aplicación desarrollada en MATLAB App Designer que permite visualizar y supervisar el comportamiento de una MicroRed híbrida mediante una interfaz gráfica interactiva.

El sistema integra fuentes de generación de energía solar y eólica, una demanda energética y un sistema de almacenamiento mediante baterías. Su propósito es representar el comportamiento energético de la MicroRed y facilitar el seguimiento de las variables principales durante una simulación.

### 2. Objetivo general

Desarrollar una aplicación interactiva que permita supervisar y analizar el comportamiento de una MicroRed híbrida, visualizando la generación energética, la demanda, el balance de potencia y el estado de carga de las baterías.

### 3. Objetivos específicos

- Representar la generación de energía solar y eólica.
- Visualizar la demanda energética del sistema.
- Supervisar el estado de carga de las baterías (SOC).
- Representar gráficamente el balance energético.
- Identificar servicios prioritarios de la MicroRed.
- Facilitar el seguimiento de las variables mediante una interfaz gráfica.

### 4. Componentes principales del sistema

**Generación solar:** representa la energía producida por los paneles solares fotovoltaicos.

**Generación eólica:** representa la energía producida por los aerogeneradores.

**Demanda energética:** representa el consumo de energía requerido por el sistema.

**Sistema de almacenamiento:** permite visualizar el estado de carga de las baterías mediante el indicador SOC (State of Charge).

**Balance energético:** permite observar la relación entre la generación disponible y la demanda energética.

### 5. Interfaz gráfica de usuario

La aplicación cuenta con un panel de supervisión que integra los siguientes elementos:

- Indicadores de generación solar, eólica y demanda.
- Controles deslizantes para visualizar y ajustar las variables energéticas.
- Indicador gráfico del estado de carga de la batería.
- Panel de servicios prioritarios.
- Gráfica de balance energético.
- Botón para iniciar la simulación.
- Botón para detener la simulación.

La interfaz utiliza un diseño visual de fondo azul oscuro, con paneles diferenciados por colores para facilitar la identificación de los componentes del sistema.

### 6. Servicios prioritarios

La aplicación contempla tres servicios prioritarios:

1. Escuela rural.
2. Bombeo de agua.
3. Alumbrado público.

Estos elementos permiten identificar las cargas representadas en el panel de supervisión de la MicroRed.

### 7. Variables principales

| Variable | Descripción | Unidad |
|---|---|---|
| Generación solar | Energía producida por paneles solares | kW |
| Generación eólica | Energía producida por aerogeneradores | kW |
| Demanda | Consumo energético del sistema | kW |
| SOC | Estado de carga de la batería | % |
| Balance energético | Diferencia entre generación y demanda | kW |

### 8. Funcionamiento de la aplicación

El funcionamiento se desarrolla mediante los siguientes pasos:

1. Se visualizan los valores de generación solar, generación eólica y demanda energética.
2. Se supervisa el estado de carga de la batería mediante el indicador SOC.
3. Se inicia la simulación utilizando el botón **INICIAR SIMULACIÓN**.
4. Durante la ejecución se visualiza el comportamiento de las variables energéticas.
5. La gráfica permite observar la generación, la demanda y el comportamiento de la batería.
6. El botón **DETENER SIMULACIÓN** permite detener la ejecución.

### 9. Herramientas utilizadas

- MATLAB R2026a.
- MATLAB App Designer.
- GitHub para el almacenamiento y publicación del proyecto.

### 10. Instrucciones de instalación y ejecución

1. Ingresar al repositorio de GitHub.
2. Descargar el archivo `SIGE_Reto4.mlapp`.
3. Abrir MATLAB R2026a.
4. Abrir el archivo desde MATLAB App Designer.
5. Ejecutar la aplicación mediante el botón **Run**.
6. Utilizar los controles de la interfaz para visualizar y supervisar la simulación.

**Requisito:** contar con MATLAB y acceso a MATLAB App Designer.

### 11. Estructura del repositorio

```text
SIGE_Reto4/
│
├── README.md
│
└── SIGE_Reto4.mlapp
```

### 12. Acceso al proyecto

**Repositorio GitHub:**

https://github.com/Caroyepes3/SIGE_Reto4

**Plataforma de desarrollo:**

https://matlab.mathworks.com/

El archivo `.mlapp` contiene la aplicación desarrollada en MATLAB App Designer, incluyendo su interfaz gráfica y programación.

Para visualizar y ejecutar la aplicación es necesario descargar el archivo y abrirlo desde MATLAB.

### 13. Conclusión

El desarrollo de SIGE Reto 4 permite representar mediante una interfaz gráfica el comportamiento de una MicroRed híbrida, integrando generación solar, generación eólica, demanda energética y almacenamiento en baterías.

La aplicación facilita la supervisión de las variables principales y la visualización del balance energético, constituyéndose en una herramienta de simulación y análisis del sistema energético propuesto.

**Proyecto académico: SIGE – Reto 4.**
