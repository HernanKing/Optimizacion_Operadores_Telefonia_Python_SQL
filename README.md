# Optimizacion_Operadores_Telefonia_Python_SQL
Propuesta de Descomposición del Proyecto Final - Telecomunicaciones: Identificación de operadores ineficaces optimizando el rendimiento de los operadores en un servicio de telefonía virtual


# Optimización de Eficiencia de Operadores en Telefonía Virtual (CallMeMaybe)

## Descripción del Proyecto
Este proyecto final se enfoca en el desarrollo de un sistema analítico para identificar operadores ineficaces dentro del servicio de telefonía virtual CallMeMaybe. El objetivo es proporcionar a los supervisores información clave para mejorar la eficiencia operativa, reducir las llamadas perdidas y optimizar los tiempos de espera, impactando directamente en la calidad del servicio y la satisfacción del cliente.

## Problema de Negocio / Objetivo
La eficiencia de los operadores es crítica para la calidad de servicio en plataformas de telefonía virtual. CallMeMaybe enfrenta el desafío de identificar a los operadores que no cumplen con los estándares de eficiencia para poder implementar mejoras. Los objetivos clave del proyecto fueron:
1.  **Identificar** patrones de ineficiencia en el rendimiento de los operadores.
2.  **Cuantificar** el impacto de los operadores ineficaces en métricas clave como llamadas perdidas y tiempos de espera.
3.  **Desarrollar un sistema/metodología** basada en datos para señalar a los operadores que requieren apoyo o reasignación.
4.  **Proporcionar recomendaciones** accionables para mejorar la eficiencia operativa y la satisfacción del cliente.

## Conjunto de Datos
El análisis se basó en un conjunto de datos que incluye registros de interacción de operadores, como:
* Registros de llamadas (duración, estado, resultado).
* Tiempos de espera de clientes.
* Número de llamadas perdidas.
* Identificadores de operador.

## Herramientas y Tecnologías Utilizadas
* **Python:** Lenguaje principal para el análisis de datos, procesamiento y desarrollo del sistema de identificación.
    * `pandas`: Para la carga, limpieza, transformación y análisis de datos de rendimiento.
    * `numpy`: Para operaciones numéricas y estadísticas.
    * `matplotlib` / `seaborn`: Para la visualización de métricas de rendimiento, distribución de tiempos, etc.
* **SQL (Conceptos):** Aplicación de lógica de bases de datos para la extracción y manipulación inicial de registros de llamadas/operadores.
* **Jupyter Notebook - VSCode:** Entorno de desarrollo para un análisis interactivo y la presentación de los hallazgos.

## Metodología y Análisis
1.  **Recopilación y Preparación de Datos:** Acceso a los registros de operadores y llamadas, limpieza de datos, manejo de valores ausentes y conversión de tipos.
2.  **Definición de Métricas de Eficiencia (KPIs):** Cálculo de indicadores clave como:
    * Tiempo promedio de manejo de llamadas (AHT).
    * Tasa de resolución en primera llamada (FCR).
    * Número de llamadas atendidas por hora/día.
    * Tasa de llamadas perdidas asociadas al operador.
    * Tiempo de inactividad.
3.  **Análisis Exploratorio de Datos (EDA):** Visualización de las distribuciones de las métricas clave para identificar variaciones en el rendimiento de los operadores.
4.  **Identificación de Operadores Ineficaces:**
    * Análisis de desempeño por operador, comparando sus métricas individuales con promedios del equipo.
    * Agrupación de operadores con K-Means para identificar perfiles de rendimiento (ej. de alto, medio, bajo rendimiento).
    * Definición de umbrales basados en métricas para clasificar a los operadores.
5.  **Análisis de Causas Raíz:** Exploración de patrones asociados con los operadores de bajo rendimiento (ej. turnos específicos, antigüedad, tipo de llamada).
6.  **Elaboración de Recomendaciones:** Traducción de los hallazgos en pasos accionables para la gerencia.

<img width="1490" height="487" alt="image" src="https://github.com/user-attachments/assets/2cb09cbf-2609-4a56-b8d6-c747a61b75f1" />

<img width="1765" height="582" alt="image" src="https://github.com/user-attachments/assets/058f7a57-63d9-4c47-9ccf-8bd43083188a" />

<img width="1764" height="579" alt="image" src="https://github.com/user-attachments/assets/31d39206-3699-452a-809e-f98017e86355" />

<img width="622" height="528" alt="image" src="https://github.com/user-attachments/assets/ffae64e7-f91e-4da4-b095-32908d5eb667" />

<img width="1187" height="490" alt="image" src="https://github.com/user-attachments/assets/e9d5487d-a041-4175-b502-8b39501691a4" />

<img width="1189" height="489" alt="image" src="https://github.com/user-attachments/assets/c399b18b-233f-4860-a58a-3ed0459d1dda" />

<img width="910" height="240" alt="image" src="https://github.com/user-attachments/assets/4fb3de63-079c-4b2f-a373-26b180d4a553" />

<img width="1816" height="557" alt="image" src="https://github.com/user-attachments/assets/8b1fedb9-00bf-41c1-b22e-66c05bbade94" />

<img width="1569" height="847" alt="image" src="https://github.com/user-attachments/assets/866b8797-7f07-4b30-9af4-cde6b86e4f2b" />

<img width="1185" height="665" alt="image" src="https://github.com/user-attachments/assets/2af615cb-7c90-4652-96e6-fe9bbce6996f" />

<img width="1184" height="669" alt="image" src="https://github.com/user-attachments/assets/306f1805-5931-4901-a64f-d145539f33db" />

<img width="1186" height="662" alt="image" src="https://github.com/user-attachments/assets/7fc058ac-0265-4602-8cb0-18229ce52a02" />











