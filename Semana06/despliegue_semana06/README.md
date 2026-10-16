## Semana 06 — Evaluación, Versionamiento y Despliegue de Modelos

### Descripción
- **Evaluación:** Entrenamiento de un clasificador de red neuronal (MLP con Keras) para predecir si lloverá mañana en Huancayo utilizando variables meteorológicas (temperatura y viento), evaluado con métricas completas (Accuracy, Precision, Recall, F1-score).
- **Versionamiento:** Comparación automatizada de dos versiones del modelo (`v1` con 8 unidades ocultas y `v2` con 24 unidades ocultas) basada en el F1-score, promoviendo automáticamente la mejor versión a producción (`modelo_produccion.keras`).
- **Despliegue:** API construida con Flask utilizando un módulo independiente de preprocesamiento (`preprocesamiento_api.py`).
- **Pruebas Automatizadas:** Pruebas unitarias implementadas con `pytest` para verificar la extracción de características y el manejo de errores ante campos faltantes.

### Uso y Ejecución de Pruebas
Para ejecutar las pruebas automatizadas de la API, corre el siguiente comando en la terminal desde la raíz del proyecto:
```bash
python -m pytest Semana_06/tests/ -v