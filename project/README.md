# Análisis y Predicción de Incendios en Brasil

## Introducción
Este proyecto analiza la tendencia histórica de incendios forestales en Brasil utilizando datos desde 1998 hasta 2016, con el objetivo de identificar patrones y realizar predicciones que permitan una mejor preparación ante futuros incendios.

## Fuente de Datos
Los datos fueron obtenidos de Kaggle y contienen registros de incendios en Brasil organizados por sectores (estados) y por año, cubriendo el período de 1998 a 2016.

**Enlace a los datos procesados:**
https://docs.google.com/spreadsheets/d/1Cn1kQ9l57QknpQ8BwSOOgXK2tYP975HQdlxLOiS9Nhk/edit?gid=1991480237#gid=1991480237

## Metodología

### Preprocesamiento de Datos
Los datos fueron procesados calculando el total de incendios registrados por año para obtener una serie temporal anual a nivel nacional de Brasil.

### Análisis Exploratorio
Se realizó un análisis exploratorio para:
- Identificar tendencias temporales
- Determinar el sector con mayor incidencia de incendios
- Visualizar la distribución de incendios a lo largo del tiempo

## Resultados

### Sector con Mayor Incidencia
El estado de **Mato Grosso** fue identificado como el sector con mayor incidencia de incendios durante el período analizado.

### Análisis de Regresión Lineal
Se aplicó un modelo de regresión lineal simple para evaluar la tendencia temporal de los incendios:

- **Pendiente (slope):** 145.581
- **Intercepto:** 1988.46
- **Coeficiente de correlación (r):** 0.3058
- **Coeficiente de determinación (r²):** ~0.094

### Interpretación de Resultados

La pendiente positiva de 145.581 indica que, en promedio, el número de incendios registrados aumenta aproximadamente 146 incendios por año.

Sin embargo, el coeficiente de correlación (r = 0.3058) sugiere una **correlación débil** entre el tiempo y el número de incendios. Esto significa que, aunque existe una tendencia al alza, otros factores no capturados en este modelo simple también influyen significativamente en la incidencia de incendios.

### Factores Contribuyentes
El incremento en los incendios puede atribuirse a múltiples factores:
- Cambios climáticos (sequías, aumento de temperaturas)
- Actividades humanas (deforestación, quemas agrícolas)
- Expansión de actividades agropecuarias
- Eventos climáticos como El Niño

## Conclusiones y Aplicaciones

Este análisis permite:
1. **Identificar una tendencia creciente** en los incendios forestales en Brasil
2. **Reconocer zonas críticas** como Mato Grosso que requieren mayor atención
3. **Proyectar escenarios futuros** para la planificación de recursos

### Recomendaciones
- Desarrollar sistemas de prevención y respuesta rápida, especialmente en Mato Grosso
- Invertir en equipos y capacitación para el combate de incendios
- Implementar políticas de monitoreo continuo durante temporadas de alto riesgo
- Considerar análisis multivariado que incluya variables climáticas y de uso de suelo para mejorar la precisión de las predicciones
