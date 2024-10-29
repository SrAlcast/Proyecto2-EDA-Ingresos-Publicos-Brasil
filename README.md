# 📊 **Proyecto 2: Análisis de la Ejecución de Ingresos Públicos en Brasil**

![Imagen](https://github.com/SrAlcast/Proyecto2-EDA-Ingresos-Publicos-Brasil/blob/main/src/DALL%C2%B7E%202024-10-29%2016.38.08%20-%20A%20professional%20PowerPoint%20background%20for%20a%20presentation%20on%20Brazilian%20government%20accounts%2C%20with%20visual%20references%20to%20economic%20data%2C%20finance%2C%20and%20govern.jpg)

## 📝 **Descripción**

Este proyecto tiene como objetivo analizar los datos históricos de la ejecución de ingresos públicos en Brasil entre los años 2013 y 2021. A través de técnicas avanzadas de análisis de datos, se busca identificar patrones en la recaudación, detectar áreas problemáticas con desvíos significativos entre lo previsto y lo recaudado, y ofrecer recomendaciones que ayuden a mejorar la precisión de las previsiones y la eficiencia en la gestión de ingresos.

El proyecto ha sido solicitado por la Secretaría de Hacienda para abordar los siguientes problemas clave:

1. **Desviaciones entre lo previsto y lo recaudado:** Identificar las categorías de ingresos con mayores discrepancias.
2. **Evolución temporal de la recaudación:** Analizar patrones de recaudación a lo largo del tiempo.
3. **Rendimiento por órgano y unidad gestora:** Evaluar la eficiencia de los diferentes órganos responsables de la recaudación.

## 🎯 **Objetivos del Proyecto**

- **Limpieza de datos:** Eliminar valores nulos, inconsistencias y duplicados.
- **Unión de conjuntos de datos:** Integrar múltiples fuentes de datos en un único dataframe para facilitar el análisis.
- **Análisis de desviaciones:** Explorar las diferencias entre lo previsto y lo recaudado en diversas categorías de ingresos.
- **Evaluación de eficiencia:** Determinar qué unidades gestoras tienen mejor rendimiento.
- **Visualización de resultados:** Crear gráficos y dashboards interactivos para visualizar los hallazgos.

## 🛠️ **Instalación y Requisitos**

Este proyecto requiere **Python 3.8+** y las siguientes bibliotecas:

- pandas
- numpy
- matplotlib
- seaborn
- plotly (opcional para dashboards interactivos)

Puedes instalar las dependencias utilizando el siguiente comando:

```bash
pip install -r requirements.txt
```

## 🚀 **Instrucciones de Uso**

1. Clona el repositorio.
2. Coloca los archivos de datos en la carpeta `data/`.
3. Ejecuta los notebooks dentro de la carpeta `notebooks/` para realizar el análisis y generar visualizaciones.
4. Explora los resultados generados y utiliza las visualizaciones interactivas para obtener insights clave.

## 📊 **Resultados Esperados**

### 1. **Análisis de Desviaciones**
Las desviaciones muestran que, en general, las proyecciones de ingresos tienden a ser optimistas, especialmente en categorías como ingresos de capital y corrientes, donde lo recaudado fue menor que lo esperado. Esto puede deberse a factores externos, como cambios en la economía, y a métodos de estimación que podrían ajustarse. Para mejorar, sería útil realizar proyecciones más conservadoras en estas categorías y considerar factores externos en las estimaciones.

### 2. **Tendencias Temporales**
Se observa un patrón estacional marcado en enero, donde los ingresos superaron con creces lo proyectado, mientras que en los otros meses las diferencias fueron menores y, en su mayoría, negativas. Esto sugiere que las proyecciones anuales no están capturando bien estos picos estacionales. Incluir ajustes estacionales permitiría que las metas mensuales reflejen mejor los cambios típicos de cada mes y mejorar la precisión de las estimaciones.

### 3. **Rendimiento por Órgano y Unidad Gestora**
Algunas unidades y órganos, como el Ministerio de Medio Ambiente y la Subsecretaría de Planeación y Presupuesto, destacan por su alto nivel de ejecución, cumpliendo o incluso superando sus metas de recaudación. En cambio, otras unidades han tenido dificultades para alcanzar sus objetivos. Analizar y replicar las prácticas de estas unidades exitosas podría ayudar a mejorar el rendimiento en otras áreas que enfrentan más desafíos.

## 🔄 **Próximos Pasos**

Acciones que se proponen para mejorar la precisión en la planificación y ejecución de los ingresos:

### 1. Ajustar las proyecciones según la estacionalidad**

Cómo hacerlo: Identificar patrones estacionales en la recaudación para ajustar las metas mensuales, en lugar de distribuirlas de manera uniforme durante el año. Por ejemplo, ajustar las previsiones para enero, un mes donde históricamente los ingresos suelen ser mayores, permitirá tener estimaciones más precisas mes a mes.

### 2. Refinar las proyecciones en categorías de ingresos variables**

Cómo hacerlo: Mejorar las proyecciones de ingresos de capital y corrientes, tomando en cuenta factores externos como el estado de la economía, los precios de recursos y las condiciones del mercado. Esto se puede lograr utilizando datos históricos y considerando variables externas para ajustar las proyecciones de forma más realista.

### 3. Aprender de las mejores prácticas de las unidades más exitosas**

Cómo hacerlo: Analizar las prácticas de unidades que han logrado altos niveles de ejecución, como el Ministerio de Medio Ambiente, para entender qué están haciendo bien. Luego, aplicar estas estrategias en otras unidades que han tenido más dificultades para alcanzar sus metas de recaudación.

### 4. Revisiones y ajustes trimestrales**

Cómo hacerlo: Establecer revisiones trimestrales para evaluar el progreso de la recaudación en relación con las metas establecidas. Esto permitirá hacer ajustes a lo largo del año, adaptando las proyecciones a medida que cambian las condiciones y mejorando la precisión de las metas.

## 🤝 **Contribuciones**

Las contribuciones son bienvenidas. Si deseas mejorar el proyecto, abre un pull request o reporta un issue.

