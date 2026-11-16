# ⚡ SIGE – SISTEMA DE GESTIÓN ENERGÉTICA
## Reto 4 – Panel de supervisión y control de una MicroRed

---

## 1. Descripción del proyecto

SIGE (Sistema de Gestión Energética) es una aplicación desarrollada en MATLAB App Designer que permite supervisar y visualizar el comportamiento de una MicroRed híbrida mediante una interfaz gráfica interactiva.

El sistema integra fuentes de generación de energía solar y eólica, demanda energética y almacenamiento mediante baterías. La aplicación permite observar el comportamiento de las variables energéticas y realizar el seguimiento del balance entre generación y consumo.

## 2. Objetivo general

Desarrollar una aplicación interactiva que permita supervisar y analizar el comportamiento de una MicroRed híbrida, visualizando la generación energética, la demanda, el balance de potencia y el estado de carga de las baterías.

## 3. Objetivos específicos

- Representar la generación de energía solar mediante paneles fotovoltaicos.
- Visualizar la generación de energía eólica mediante aerogeneradores.
- Supervisar la demanda energética del sistema.
- Monitorear el estado de carga de las baterías (SOC).
- Visualizar gráficamente el balance energético.
- Identificar los servicios prioritarios de la MicroRed.
- Facilitar la supervisión de las variables mediante una interfaz gráfica.

## 4. Componentes principales del sistema

**Generación solar:** representa la energía producida por los paneles solares fotovoltaicos.

**Generación eólica:** representa la energía producida por los aerogeneradores.

**Demanda energética:** representa el consumo de energía requerido por el sistema.

**Sistema de almacenamiento:** permite visualizar el estado de carga de las baterías mediante el indicador SOC (State of Charge).

**Balance energético:** permite observar la relación entre la generación disponible y la demanda energética.

## 5. Interfaz gráfica de usuario

La aplicación cuenta con un panel de supervisión que integra:

- Indicadores de generación solar, eólica y demanda.
- Controles deslizantes para ajustar las variables energéticas.
- Indicador gráfico del estado de carga de la batería.
- Panel de servicios prioritarios.
- Gráfica de balance energético.
- Botón para iniciar la simulación.
- Botón para detener la simulación.

La interfaz utiliza un diseño visual de fondo azul oscuro, con paneles diferenciados por colores para facilitar la identificación de los componentes del sistema.

## 6. Servicios prioritarios

La aplicación contempla tres servicios prioritarios:

1. Escuela rural.
2. Bombeo de agua.
3. Alumbrado público.

Estos servicios representan cargas importantes dentro de la MicroRed y permiten visualizar su estado en el panel de supervisión.

## 7. Variables principales

| Variable | Descripción | Unidad |
|---|---|---|
| Generación solar | Energía producida por paneles solares | kW |
| Generación eólica | Energía producida por aerogeneradores | kW |
| Demanda | Consumo energético del sistema | kW |
| SOC | Estado de carga de la batería | % |
| Balance energético | Diferencia entre generación y demanda | kW |

## 8. Funcionamiento de la aplicación

El funcionamiento se desarrolla mediante los siguientes pasos:

1. Se visualizan los valores de generación solar, generación eólica y demanda energética.
2. Se supervisa el estado de carga de la batería mediante el indicador SOC.
3. Se inicia la simulación mediante el botón **INICIAR SIMULACIÓN**.
4. Durante la ejecución se visualiza el comportamiento de las variables energéticas.
5. La gráfica permite observar la generación, la demanda y el comportamiento de la batería.
6. El botón **DETENER SIMULACIÓN** permite detener la ejecución.

## 9. Herramientas utilizadas

- MATLAB R2026a.
- MATLAB App Designer.
- MATLAB Drive.
- GitHub para el almacenamiento y publicación del proyecto.

## 10. Instrucciones de ejecución

1. Descargar el archivo `SIGE_Reto4.mlapp` desde el repositorio.
2. Abrir MATLAB R2026a.
3. Abrir el archivo desde MATLAB App Designer.
4. Ejecutar la aplicación mediante el botón **Run**.
5. Utilizar los controles de la interfaz para visualizar y supervisar la simulación.

**Requisito:** disponer de MATLAB con acceso a App Designer.

## 11. Estructura del repositorio

```text
SIGE_Reto4/
│
├── README.md
├── SIGE_Reto4.mlapp
└── SIGE_Reto4_codigo.m
```

- `README.md`: documentación y descripción del proyecto.
- `SIGE_Reto4.mlapp`: aplicación principal desarrollada en MATLAB App Designer.
- `SIGE_Reto4_codigo.m`: código fuente exportado desde MATLAB App Designer para consulta de la programación.

## 12. Enlaces de acceso al proyecto

### Plataforma de desarrollo

[Ingresar a MATLAB Online](https://matlab.mathworks.com/)

### Aplicación principal

[Descargar SIGE_Reto4.mlapp desde GitHub](https://github.com/Caroyepes3/SIGE_Reto4/blob/main/SIGE_Reto4.mlapp)

### Código fuente MATLAB

[Consultar código fuente SIGE_Reto4_codigo.m](https://drive.mathworks.com/sharing/6faa7c1d-6b16-4a39-a1ec-07eec1e23938/SIGE_Reto4_codigo.m)

### Repositorio GitHub

[Consultar repositorio SIGE_Reto4](https://github.com/Caroyepes3/SIGE_Reto4)

**Nota:** Para ejecutar la aplicación es necesario descargar el archivo `.mlapp` y abrirlo en MATLAB App Designer. El archivo `.m` permite consultar la programación exportada de la aplicación.

## 13. Conclusión

El desarrollo de SIGE Reto 4 permite representar mediante una interfaz gráfica el comportamiento de una MicroRed híbrida, integrando generación solar, generación eólica, demanda energética y almacenamiento en baterías.

La aplicación facilita la supervisión de las variables principales y la visualización del balance energético, constituyéndose en una herramienta de simulación y análisis del sistema energético propuesto.

---

**Proyecto académico: SIGE – Reto 4.**
