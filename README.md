  # <h1 align="center"> Plataforma de Análisis Interactivo y Modelo de Predicción de Emisiones de Carbono en Taxis de NYC: Información Accesible para Decisiones Sostenibles y Basadas en Datos</h1>

![kpi](https://github.com/AlarconIlbert/Proyecto-AIMPEC/assets/73408508/dcc69142-9d84-4663-86cf-406607d572ca)

![0240](https://github.com/AlarconIlbert/Proyecto-AIMPEC/assets/73408508/3e07341e-9ae1-4eca-990d-5ff1f2f3e411)


 ## <h2 align='left'> 1. Descripcion del Proyecto </h2>
 El proyecto "NYC Taxis & Carbon Emission" se centra en analizar datos relacionados con el sector de taxis en la ciudad de Nueva York, específicamente en cuanto a su impacto en la contaminación del aire y el ruido. El objetivo principal es comprender los patrones de uso de los taxis, las emisiones que generan y cómo esto afecta la calidad del aire y la contaminación acústica en la ciudad.
 
 La empresa de servicios de transporte de pasajeros que ha contratado el proyecto tiene interés en expandirse al sector de los taxis y desea obtener información precisa para tomar decisiones informadas. Su visión a futuro incluye la posibilidad de incorporar vehículos eléctricos a su flota, lo que podría reducir la contaminación y mejorar la calidad del aire.

 ## <h2 align='left'>  2. Gestión del Proyecto </h2>
<p align="justify">En este proyecto se está trabajando con la metodología ágil bajo el marco de trabajo Scrum. Esto implica la aplicación de los valores y principios ágiles en nuestro  enfoque de desarrollo de software,donde se  utiliza la estructura de roles, eventos, artefactos y reglas de Scrum para organizar y gestionar el trabajo en equipo.</p>

 - **Sprint01**: Limpieza de datos(HU001).
 - **Sprint02**: Integración de datos(HU002),Análisis exploratorio de datos(HU003).
 - **Sprint03**: Modelo de predicción(HU004),Desarrollo de Dashboard(HU005),Validación de Dashboard(HU006),Despliegue en la nube(HU007).

 ## <h3 align='left'>  2.1 Artefactos de Scrum</h3>
En Scrum, utilizaremos diferentes artefactos para facilitar la planificación, seguimiento y comunicación del proyecto. A continuación, detallamos qué representan cada uno de los artefactos:
 - **Lienzo Lean (Canvas):**
   El lienzo Canvas, también conocido como Business Model Canvas, es una herramienta utilizada en la fase de planificación inicial del proyecto. Que nos  Permitió visualizar y definir de manera concisa los aspectos clave del modelo de negocio, como los segmentos de clientes, propuesta de valor, canales de distribución, fuentes de ingresos, etc. [Link Lienzo Canvas](https://miro.com/welcomeonboard/Z3hMeUV1em1MdjRiSkF2aVd2ZVdHMHVNdzhMQXUzR2l1czM2VThJTEF1OURVdmsya29LanFxelZXaVNtcVFjdHwzMDc0NDU3MzU5MTY3OTkyOTUwfDI=?share_link_id=234733872676)
 - **Tablero Kanban (Kanban Board):**
   El tablero Kanban es una herramienta visual utilizada para el seguimiento y gestión de las tareas y el flujo de trabajo en nuestro proyecto.Se usó la ClickUp para representar las diferentes etapas del proceso de desarrollo y las tareas  a lo largo del tablero a medida que avanzan en cada sprint. [Link Tablero Kanban](https://sharing.clickup.com/9003183105/b/h/6-900302462589-2/2f84773b6c7934d)
 - **Cronograma Gantt (Gantt Chart):**
El cronograma Gantt es una representación gráfica de nuestro  plan de proyecto que muestra las tareas, su duración, secuencia y dependencias en forma de un gráfico de barras. Muestra visualmente la planificación temporal del proyecto y permite gestionar las fechas de inicio y finalización de las tareas por sprint. [Link Gantt Chart](https://sharing.clickup.com/9003183105/g/h/8ca3b01-402/44904377e385669)


 ## 3. Objetivo general del proyecto
  Es de optimizar los servicios de taxis en NYC, identificando patrones de demanda y oportunidades de mejora. Se desarrollará un modelo de pronóstico con una precisión del 98% para estimar las emisiones de carbono, impulsando decisiones más sostenibles y eficientes.
  ## <h3 align='left'>  3.1 Objetivos especificos.</h3>
  -	**OE-01:** Definir el alcance del proyecto y establecer la infraestructura necesaria, utilizando metodologías ágiles. Colaborar en la organización y distribución de tareas, asignando roles específicos y creando el repositorio de código, fuentes de datos y documentación.
  -	**OE-02:** Implementar pipelines de extracción, transformación y carga (ETL) de datos hacia estructuras de almacenamiento, como Data Warehouse, Data Lake o Data Lakehouse. Considerar la carga incremental de datos y utilizar herramientas de big data y/o servicios en la nube para optimizar el proceso.
  - **OE-03:** Desarrollar un dashboard interactivo y un modelo de Machine Learning utilizando los datos procesados. Incluir los KPIs relevantes para el análisis realizado y preparar un storytelling efectivo para presentar los resultados. Elaborar reportes y dashboards, definir y calcular los KPIs, y poner en producción el modelo de Machine Learning.


## 4. Desarrollo de la solucion
La solución permitirá visualizar de manera intuitiva y en tiempo real diversos indicadores claves. Además, se desarrollará un modelo de predicción basado en técnicas de machine learning, que utilizará datos históricos y variables relevantes para estimar las emisiones de carbono generadas por los taxis y se utilizarán tecnologías como Hugging Face para el desarrollo del modelo de predicción y Power BI para la creación del dashboard interactivo.
 Con esta solución, el cliente podrá obtener información en tiempo real, identificar patrones y tendencias, y tomar decisiones informadas y sostenibles para mejorar la eficiencia y calidad del servicio de taxis. 
![image](https://github.com/AlarconIlbert/PF_GRUPO09/assets/73408508/cf88fc4f-e2a7-458b-a973-89cc02cff62d)

   
## 5. ETL/EDA
  ## <h3 align='left'>  5.1 ETL (Extracción, Transformación y Carga de datos):</h3>
  - **Databricks:** Plataforma que proporciona un entorno de trabajo colaborativo para realizar tareas de ETL y análisis de datos utilizando herramientas como PySpark.
  - **Jupyter Notebook:** Entorno interactivo de programación que permite escribir y ejecutar código en Python para realizar tareas de extracción y transformación de datos.
  - **Beautiful Soup:** Biblioteca de Python utilizada para el scraping web, permitiendo extraer datos de páginas HTML o XML.
  ## <h3 align='left'>  5.2 EDA (Analisis Exploratorio de los Datos):</h3>
  - **Identificación de insights:** Este proceso consta de analizar relaciones y patrones realizando un análisis exploratorio más profundo para identificar relaciones y patrones interesantes entre variables, 
Identificando valores atípicos para buscar excepciones que puedan proporcionar información relevante o insights únicos, realizando análisis comparativo en diferentes grupos o segmentos para identificar valores significativos y obtener insights adicionales, como por ejemplo la investigación de features como CO2, contaminación sonora, combustión y CO2.

Gráfico de barras sobre la cantidad de viajes por año:
<p align=center><img src= Sprint03/Imagen5.jpg><p>

- **Segmentación y agrupación:** Examinar las características y comportamientos de cada segmento para comprender mejor las diferencias y similitudes entre ellos.
 <p align=center><img src= Sprint03/Imagen7.jpg><p>
  
 - **Análisis estadístico:** Los valores estadísticos se identificaron para las variables numéricas validando la media, mediana y moda.
<p align=center><img src= Sprint03/Imagen6.jpg><p>

Los aspectos más importantes de este proceso se pueden consultar en: [ETL](https://github.com/AlarconIlbert/PF_GRUPO09/tree/master/Sprint02%20/ETL) y el [EDA](https://github.com/AlarconIlbert/PF_GRUPO09/tree/master/Sprint02%20/EDA "EDA").

## 6. Indicadores de exito (KPIs)
- Reducción de la emisión de contaminantes.
- Aumento de viajes compartidos
- Mejora de la eficiencia de los conductores
- Aumento de los ingresos

## 6. Conclusiones
El proyecto "NYC Taxis & Carbon Emission" proporcionó con éxito una comprensión integral de los patrones de uso de taxis, el impacto de las emisiones y las oportunidades de mejora. Los hallazgos destacaron el potencial para reducir la contaminación, aumentar los viajes compartidos, mejorar la eficiencia del conductor y aumentar los ingresos. Con estos conocimientos, la empresa de servicios de transporte de pasajeros puede tomar decisiones informadas, incorporando potencialmente vehículos eléctricos a su flota y contribuyendo a un ecosistema de transporte más ecológico y sostenible en la ciudad de Nueva York.[Click  Aquí para visualizar nuestro MVP: TAXI GREENTRENDZ](https://app.fabric.microsoft.com/view?r=eyJrIjoiMjllYmYxZGEtZjJiZC00YjJiLWEzODktNWVkNDAyN2ViZjZkIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)
  
 ## 7. Documentacion
 El presente documento proporciona una documentación completa del proyecto "NYC Taxis & Carbon Emission". Este documento servirá como guía para la empresa de servicios de transporte de pasajeros. [Click Aquí para ver la Documentacion con metodologías ágiles](https://www.canva.com/design/DAFpO0NgijU/MKXwhSCVm8g6_gNb7tYyFg/view?utm_content=DAFpO0NgijU&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink)

 ### Team Scrum

![image](https://github.com/AlarconIlbert/Proyecto-AIMPEC/assets/73408508/a1df2028-97bc-4ff7-9d13-bf2be67cfa2b)



<a href="https://www.linkedin.com/in/oscardavidhospinal"><img alt="David Hospinal " title="Connect with David" src="https://img.shields.io/badge/David Hospinal-0077B5?style=flat&logo=Linkedin&logoColor=white"></a> **PROJECT MANAGER & CLOUD ARCHITECT**

<a href="https://www.linkedin.com/in/leandro-jofr%C3%A9-0a8834103/"><img alt="Leandro" title="Connect with Leandro" src="https://img.shields.io/badge/Leandro Jofré -0077B5?style=flat&logo=Linkedin&logoColor=white"></a> **DATA ENGINEER**

<a href="https://www.linkedin.com/in/pedro-oria-395376251/"><img alt="Pedro" title="Connect with Leandro" src="https://img.shields.io/badge/Pedro Oria -0077B5?style=flat&logo=Linkedin&logoColor=white"></a> **DATA ENGINEER**

<a href="https://www.linkedin.com/in/ilbert-ferney-alarcon-bothia/"><img alt="Ilbert" title="Connect with Ivanna" src="https://img.shields.io/badge/Ilbert Alarcón-0077B5?style=flat&logo=Linkedin&logoColor=white"></a> **DATA SCIENCE**

<a href="https://www.linkedin.com/in/juliana-caceres-260388241/"><img alt="Juliana" title="Connect with Juliana" src="https://img.shields.io/badge/Juliana Cáceres-0077B5?style=flat&logo=Linkedin&logoColor=white"></a> **DATA ANALYST**

 
# Citación
Por favor si usas la base de datos o el código, realizar la citación respectiva a los  autores. 
```
  Title = {AIMPEC},
  Authors = {David Hospinal , Leandro Jofré, Ilbert Alarcón,Pedro Oria,Juliana Cáceres},
  Year = {2023}
  University={HENRY}
}
```
# Contacto 
Para mas información por favor contactarse a:

oscardavid.hospinal@uc.cl(David Hospinal).



