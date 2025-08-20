# TelecomX_Alura_Challenge
Telecom X - Análisis de Evasión de Clientes
Análisis de Evasión de Clientes (Churn) en Telecomunicaciones
Descripción del Proyecto
Este proyecto tiene como objetivo analizar y comprender los factores que influyen en la evasión de clientes (Churn) en una empresa de telecomunicaciones. A través del análisis exploratorio de datos (EDA), la limpieza y transformación de datos, y el análisis de correlación, buscamos identificar patrones y obtener insights para reducir la tasa de Churn.

Datos
Los datos utilizados en este análisis provienen de un archivo JSON disponible en el siguiente enlace:

https://raw.githubusercontent.com/ingridcristh/challenge2-data-science-LATAM/main/TelecomX_Data.json

Este conjunto de datos contiene información sobre clientes de una empresa de telecomunicaciones, incluyendo datos demográficos, servicios contratados, información de la cuenta y si el cliente ha evadido el servicio (Churn).

Análisis Realizado
El análisis se llevó a cabo en un notebook de Google Colab e incluyó los siguientes pasos:

Carga y exploración inicial de datos: Se cargaron los datos desde la fuente JSON y se realizó una exploración inicial para comprender la estructura y el contenido del dataset.
Limpieza y tratamiento de datos: Se normalizaron las columnas anidadas, se verificaron los valores ausentes y duplicados, y se transformaron variables categóricas binarias a formato numérico.
Análisis Exploratorio de Datos (AED): Se realizaron visualizaciones para analizar la distribución de la variable objetivo (Churn) y su relación con variables categóricas y numéricas.
Análisis de Correlación: Se calculó y visualizó la matriz de correlación para identificar la relación entre diferentes variables y la evasión de clientes.
Hallazgos Clave e Insights
Los principales hallazgos del análisis sugieren que los siguientes factores están más relacionados con la evasión de clientes:

Clientes con menor antigüedad ("tenure").
Clientes con contratos mes a mes.
Clientes con servicio de Internet de fibra óptica.
Clientes que no tienen servicios adicionales como seguridad en línea, respaldo en línea, protección de dispositivos y soporte técnico.
Clientes que utilizan el pago electrónico ("Electronic check").
Clientes de la tercera edad ("SeniorCitizen").
Clientes sin pareja o dependientes.
Clientes con cargos mensuales más altos.
Recomendaciones Estratégicas
Basado en los insights obtenidos, se proponen las siguientes recomendaciones para reducir la evasión de clientes:

Implementar programas de retención para clientes con contratos mes a mes, ofreciendo incentivos para contratos más largos.
Promover la adopción de servicios adicionales para aumentar la retención.
Investigar y abordar las razones detrás de la alta tasa de Churn en clientes con fibra óptica.
Implementar programas de fidelización para clientes nuevos durante los primeros meses de servicio.
Analizar en detalle la relación entre el método de pago electrónico y la evasión, y considerar mejoras en la experiencia de pago.
Segmentar a los clientes en riesgo de evasión y ofrecer ofertas personalizadas.
Diseñar estrategias y servicios para mejorar la satisfacción de los clientes de la tercera edad.
Cómo Ejecutar el Notebook
Puedes ejecutar el análisis completo abriendo el archivo del notebook en Google Colab. Asegúrate de tener las bibliotecas necesarias instaladas (pandas, requests, matplotlib, seaborn).

Contribuciones
Las contribuciones a este proyecto son bienvenidas. Si deseas contribuir, por favor, haz un fork del repositorio y envía un pull request con tus cambios.
