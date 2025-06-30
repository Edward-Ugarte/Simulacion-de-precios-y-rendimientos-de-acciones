# Simulacion-de-precios-y-rendimientos-de-acciones
# 📈 Simulación de Precios y Rendimientos de Acciones – Edward Ugarte

Este proyecto reproduce una simulación de precios de acciones y rendimientos logarítmicos diarios para **tres empresas hipotéticas**, utilizando herramientas del software econométrico **Gretl 2025b**. Su propósito es ilustrar dinámicas de retorno, volatilidad y covarianza en activos financieros, como base para ejercicios de análisis de portafolio.

## 📦 Contenidos

- `acciones_simuladas.gdt`: Base de datos generada con precios y rendimientos simulados
- `precios_y_rendimientos.csv`: Exportación en formato tabular (para R, Excel, Python, etc.)
- `simulacion_acciones.inp`: Script de Gretl con documentación clara y resultados imprimibles

## 🎯 Objetivos

- Simular trayectorias de precios realistas con comportamiento log-normal
- Calcular rendimientos logarítmicos diarios
- Estimar estadísticas básicas de retorno y riesgo
- Construir una matriz de covarianzas simétrica y alineada para interpretación
- Dejar preparada la base para construir la frontera eficiente de Markowitz

## 🧠 Detalles técnicos

- 100 observaciones simuladas (días)
- Choques generados con distribución normal
- Precios generados como caminatas geométricas aleatorias
- Rendimientos calculados como diferencias logarítmicas
- Covarianzas presentadas con alineación de columnas en consola Gretl

## 📝 Ejemplo de salida esperada
