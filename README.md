#📞 Proyecto: Análisis de Comportamiento del Cliente y Optimización de Tarifas (Megaline)

## 🎯 Visión General del Proyecto ##

Este proyecto se centra en el análisis del comportamiento de los clientes y la determinación de la tarifa de prepago más rentable (Surf vs. Ultimate) para el operador de telecomunicaciones Megaline. Abordamos el desafío de trabajar con datos de consumo de 500 clientes, incluyendo llamadas, mensajes e internet, para entender cómo estos patrones impactan en los ingresos de la compañía.

El objetivo principal fue realizar un análisis preliminar de las tarifas para identificar cuál de ellas genera mayores ingresos, lo que permitirá al departamento comercial de Megaline ajustar su presupuesto de publicidad y estrategias de marketing de manera informada. Este estudio proporciona una base de datos robusta y insights accionables para la toma de decisiones estratégicas.

## ✨ Habilidades Clave Demostradas
# 💻 Hard Skills:
- **Preprocesamiento de Datos Avanzado:** Limpieza y transformación de conjuntos de datos con valores ausentes y corrección de tipos de datos (datetime, object, int) en un entorno de múltiples tablas.
- **Manipulación de Datos con Pandas:** Dominio en la integración y consolidación de información de diversas tablas (merge, groupby), así como filtrado y agregación compleja para calcular métricas mensuales.
- **Análisis Exploratorio de Datos (EDA):** Capacidad para identificar la estructura de los datos, detectar problemas de calidad y comprender distribuciones del comportamiento de uso (llamadas, mensajes, internet) e ingresos en grandes volúmenes de información.
- **Ingeniería de Características:** Creación de nuevas columnas para el mes de actividad, el exceso de uso por servicio (extra_minutes, extra_messages, extra_gb) y el cálculo del ingreso total mensual por cliente (total_revenue).
- **Estadística Aplicada y Prueba de Hipótesis:** Aplicación de pruebas t de Student para comparar medias y la prueba de Levene para varianzas, validando diferencias significativas en los ingresos y el comportamiento de uso.
- **Visualización de Datos:** Creación de gráficos informativos (histogramas, diagramas de caja, gráficos de barras) utilizando Matplotlib y Seaborn para comunicar hallazgos clave.
- **Programación Python:** Aplicación de lógica modular para el procesamiento eficiente y escalable de datos.

# 🤝 Soft Skills:
- **Pensamiento Crítico:** Capacidad para formular hipótesis claras y evaluar rigurosamente la rentabilidad de las tarifas y el impacto regional, basándose en evidencia estadística.
- **Atención al Detalle:** Rigurosidad en la identificación y corrección de inconsistencias en los datos y en la interpretación precisa de los resultados.
- **Resolución de Problemas:** Habilidad para abordar desafíos comunes en la calidad de datos y la lógica de negocio para el cálculo de ingresos por uso.
- **Orientación a Resultados:** Enfoque en entregar insights claros y accionables que respondan a la pregunta de negocio central sobre la rentabilidad de las tarifas.
- **Organización del Proyecto:** Estructuración del proceso de análisis en etapas claras y manejables, desde la inicialización hasta las conclusiones finales.
- **Comunicación Efectiva:** Habilidad para presentar los hallazgos técnicos y estadísticos de manera comprensible para una audiencia de negocios.

## 📊 Aspectos Destacados del Análisis
- **Preparación y Limpieza Integral de Datos:** Carga, inspección y corrección de cinco conjuntos de datos relacionados (usuarios, llamadas, mensajes, internet, planes) para su posterior integración, incluyendo la gestión de fechas y la imputación de valores nulos relevantes.
- **Agregación de Datos Mensuales:** Consolidación exitosa del uso de servicios (llamadas, minutos, mensajes, GB de internet) a nivel mensual por cada usuario.
- **Cálculo Preciso de Ingresos:** Determinación del ingreso total mensual por cliente, considerando el costo base de su plan y calculando detalladamente los cargos adicionales por excedentes en cada servicio.
- **Análisis Comparativo Profundo por Tarifa:** Estudio del promedio y la distribución del uso de llamadas, mensajes, consumo de internet y los ingresos generados para los planes Surf y Ultimate, identificando patrones de consumo y áreas de potencial beneficio.
- **Validación Estadística Rigurosa:** Implementación de pruebas de hipótesis para determinar si las diferencias en ingresos y patrones de uso entre planes son estadísticamente significativas, así como para comparar los ingresos entre usuarios de la región NY-NJ y otras regiones.
- **Detección de Oportunidades de Negocio:** Identificación de usuarios con alto consumo en el plan "Surf" que podrían ser candidatos para una invitación al plan "Ultimate", optimizando así los ingresos por cliente.
 
## 🛠️ Tecnologías Utilizadas
- Python
-Pandas (para manipulación y análisis de datos)
- NumPy (para operaciones numéricas y matemáticas)
- Matplotlib (para visualización de datos)
- Seaborn (para visualización estadística y gráficos avanzados)
- SciPy.stats (para pruebas estadísticas y funciones de distribución)
- Jupyter Notebook (para el desarrollo interactivo y la documentación)

# 📂 Resumen Ejecutivo
Análisis de registros de clientes prepago con pandas para comparar ingresos generados por planes prediseñados, analizando llamadas, mensajes, consumo de datos y cargos extras. Identifiqué usuarios con patrones de sobreuso que representan oportunidades de migración de plan, y validé que el plan más rentable para la empresa es aquel con mayor probabilidad de consumo adicional.

Analyzed prepaid customer records with pandas to compare revenue from predefined plans, examining calls, messages, data usage, and overage charges. Identified overuse patterns suggesting upgrade opportunities, and confirmed that the most profitable plan is the one with a higher likelihood of exceeding usage limits.

Id_project: 05

