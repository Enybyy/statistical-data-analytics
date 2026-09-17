# 📊 Statistical Data Analytics — Inferencia Estadística, BI y Detección de Anomalías
> **Análisis estadístico riguroso, pruebas de hipótesis (A/B Testing), detección de anomalías/fraude y consultas avanzadas SQL en bases de datos empresariales.**

[![Python](https://img.shields.io/badge/Python-3.x-3776ab.svg)](https://www.python.org/)
[![SQL](https://img.shields.io/badge/Database-SQL%20%7C%20SQLite-003B57.svg)](#-consultas-avanzadas-sql)
[![Statistics](https://img.shields.io/badge/Stats-Inferential%20%7C%20Probability-blue.svg)](#-principales-módulos-analíticos)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## 📌 El Desafío de Negocio

En la era del Big Data, recopilar datos es fácil; lo difícil es **extraer conclusiones estadísticamente válidas que no lleven a errores costosos**. Las empresas enfrentan riesgos críticos:

- **Falsos Positivos en Decisiones de Producto y Marketing**: Implementar cambios basados en aumentos de ventas pasajeros sin validar significancia estadística mediante pruebas de hipótesis conduce a desperdicio de presupuesto.
- **Riesgo por Fraude Transaccional**: No contar con modelos probabilísticos para detectar transacciones atípicas permite que operaciones fraudulentas pasen desapercibidas hasta que generan pérdidas irreparables.
- **Silos de Información Relacional**: Incapacidad de consultar y transformar esquemas complejos de bases de datos relacionales en métricas comerciales ejecutivas.

---

## 💡 La Solución Implementada

Este repositorio reúne un arsenal de **técnicas estadísticas avanzadas, modelos probabilísticos y análisis de bases de datos relacionales** aplicadas a escenarios empresariales:

### 1. Inferencia Estadística & Pruebas de Hipótesis (`Estadistica/Inferencial`)
- **Validación con p-valor y Significancia Estadística**: Implementación de pruebas z, pruebas t de Student y análisis de varianza para validar experimentos (A/B testing) con rigor científico.
- **Intervalos de Confianza**: Estimación de rangos de incertidumbre para métricas clave de negocio (tasas de conversión, tiempos de respuesta, ingresos promedio).
- **Modelos de Regresión Lineal y Multivariada**: Identificación del impacto relativo de variables predictoras sobre resultados de negocio (ej. ventas vs inversión publicitaria).

### 2. Probabilidad y Detección de Anomalías / Fraude (`Estadistica/Probrabilidad`)
- **Detección de Transacciones Fraudulentas (`transac_frauduletas.ipynb`)**: Modelado estocástico para detectar comportamientos atípicos en registros financieros y alertar operaciones sospechosas en tiempo real.
- **Distribuciones Teóricas vs Empíricas**: Ajuste de distribuciones normales y binomiales para modelar fenómenos de mercado.

### 3. Estadística Descriptiva y Análisis de Mercado (`Estadistica/Descriptiva`)
- Exploración de dispersión, sesgo y medidas de tendencia central en datos reales de e-commerce (precios en Amazon) y volatilidad en activos digitales (Ethereum).

### 4. Consultas y Modelado de Datos Relacionales con SQL (`FreeCodeCamp`)
- Integración de Python con motores SQLite sobre bases de datos de referencia empresarial (`sakila.db`, `chinook.db`, `sales_data.csv`).
- Joins complejos, funciones de ventana (*window functions*), agregaciones y extracción de KPIs comerciales para paneles de Business Intelligence.

---

## 📈 Impacto y Mejoras Conseguidas

| Enfoque Empírico Común | Con Análisis Estadístico Riguroso | Beneficio Empresarial Directo |
|---|---|---|
| **Decisiones por intuición o modas** | Validación formal con pruebas de hipótesis y p-valor | **Certeza matemática antes de comprometer inversiones de capital** |
| **Monitoreo pasivo de transacciones** | Algoritmos de detección de transacciones atípicas | **Prevención activa de fraudes y reducción de chargebacks** |
| **Reportes descriptivos planos** | Modelos de regresión inferencial | **Comprensión de causalidad: qué palancas realmente mueven el negocio** |
| **Consultas SQL lentas y desconectadas** | Pipelines reproducibles en Python + SQL | **Extracción de métricas de ventas confiables en minutos** |

---

## 🗂️ Estructura del Repositorio

```text
├── Estadistica/
│   ├── Descriptiva/               # Tendencia central, dispersión y análisis de mercado
│   │   ├── Histograma.ipynb
│   │   ├── Mean_Median_Mode.ipynb
│   │   └── data/ (precios_amazon.csv, precios_ethereum.csv)
│   │
│   ├── Inferencial/               # Inferencia, regresión y pruebas de hipótesis
│   │   ├── inferencia_p-valor.ipynb
│   │   ├── intervalos_confianza.ipynb
│   │   ├── regresión_lineal.ipynb
│   │   └── aprendizaje_supervisado.ipynb
│   │
│   └── Probrabilidad/             # Modelos probabilísticos y detección de fraude
│       ├── transac_frauduletas.ipynb   # Detección de transacciones anómalas
│       └── distribución_normal.ipynb
│
├── FreeCodeCamp/                  # Consultas analíticas SQL en SQLite
│   ├── data/ (sakila.db, chinook.db, sales_data.csv)
│   └── Exercises & Lectures.ipynb
│
└── README.md                      # Documentación del repositorio
```

---

## 🛠️ Stack Tecnológico

- **Lenguaje**: Python 3.
- **Bases de Datos & SQL**: SQLite, SQL Alchemy, SQLite3.
- **Librerías Científicas**: SciPy, Statsmodels, NumPy.
- **Manipulación de Datos**: Pandas.
- **Visualización Analítica**: Seaborn, Matplotlib.
- **Entorno**: Jupyter Notebooks.

---

## 🚀 Cómo Explorar los Cuadernos

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/Enybyy/statistical-data-analytics.git
   cd statistical-data-analytics
   ```

2. **Instalar dependencias requeridas:**
   ```bash
   pip install jupyter pandas numpy scipy statsmodels matplotlib seaborn
   ```

3. **Iniciar Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   Navega a las carpetas `Estadistica/Inferencial/` o `Estadistica/Probrabilidad/` para ver los análisis paso a paso.

---

## 📬 ¿Necesitas validar decisiones o construir analítica sólida en tu empresa?

Ofrezco servicios profesionales de **consultoría en Business Intelligence, análisis estadístico para toma de decisiones, experimentación / A/B Testing y detección de anomalías en datos de negocio**.

- **GitHub**: [@Enybyy](https://github.com/Enybyy)
- **Perfil Profesional**: Eliud RM — Data Science & Software Solutions
- *Conversemos sobre cómo respaldar la estrategia de tu negocio con datos y rigor analítico.* 

