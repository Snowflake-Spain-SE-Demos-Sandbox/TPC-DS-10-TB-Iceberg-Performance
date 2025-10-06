# Rendimiento de consultas sobre 10 Terabytes en tablas Iceberg gestionadas por Snowflake

## Tutorial TPC-DS: Micro-particiones y Data Clustering

---

### Bienvenido

Este notebook es un tutorial práctico que demuestra las capacidades de rendimiento de Snowflake al ejecutar consultas analíticas complejas sobre un dataset de **10 Terabytes en formato Iceberg** utilizando el benchmark estándar de la industria **TPC-DS**.

**Instrucciones:**
Desde tu cuenta de Snowflake, crea un nuevo Notebook con la opción **Import** del archivo 

**Objetivos de aprendizaje:**
1. Comprender el modelo de datos TPC-DS en formato Iceberg
2. Entender las **micro-particiones** de Snowflake y su impacto en el rendimiento
3. Dominar el **clustering de datos** para optimizar consultas en tablas Iceberg
4. Ejecutar y analizar consultas del benchmark TPC-DS
5. Medir y comparar el rendimiento con diferentes estrategias de optimización
6. Comparar el comportamiento de tablas Iceberg vs formato nativo Snowflake

**Referencias:**
- [TPC-DS Sample Data](https://docs.snowflake.com/en/user-guide/sample-data-tpcds)
- [TPC-DS Queries (99 queries)](https://docs.snowflake.com/en/_downloads/0eec2c68e78863a07eb994c85e76b188/tpc-ds-all-queries.sql)

---
