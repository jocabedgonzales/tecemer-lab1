# TecEmer Lab 1

Proyecto de laboratorio para consumir una API pública de chistes usando Python y la librería `requests`.

## Instalación

1. Crear y activar el entorno virtual:

```powershell
python -m venv .venv
.venv\Scripts\activate
```

2. Instalar las dependencias:

```powershell
pip install -e .
```

## Uso

```powershell
python src\tecemer_lab1\app.py
```

El programa consulta una API pública e imprime un chiste en inglés.

## Estructura del proyecto

```text
tecemer-lab1/
├── src/
│   └── tecemer_lab1/
│       ├── __init__.py
│       └── app.py
├── .gitignore
├── pyproject.toml
├── requirements.txt
└── README.md
```

## Autor y curso

Jocabed Gonzales Quispe  
Tecnologías Emergentes - ISO46B


## Laboratorio 02: Librerías para datos

En este laboratorio se utilizó NumPy para realizar operaciones vectorizadas y estadísticas básicas.

También se consumió la API Open-Meteo para obtener el pronóstico de siete días de Huancayo. La respuesta JSON se guardó como respaldo y se convirtió a CSV.

Finalmente, con Pandas se transformaron los datos: se calculó la amplitud térmica, se identificaron días lluviosos y se clasificaron las temperaturas en categorías. Los resultados procesados y el resumen por categoría se exportaron en archivos CSV.