# Proyecto Final – Visualización de Datos y Storytelling 📊

Este repositorio contiene el proyecto final del ramo **Visualización de Datos y Storytelling**, donde se analiza información real y sintética relacionada con COVID-19 mediante técnicas de exploración, visualización y narrativa de datos en Python.

El análisis principal está implementado en el notebook:

- `src/index_proyecto_grupal.ipynb`

Tambien, dejamos link del chat que utilizamos para el desrrollo de esta actividad:
👉 Visita Chat: https://gemini.google.com/share/1cdc5fa76e92

---

## 🚀 1. Requisitos previos

Antes de comenzar, asegúrate de tener instalado:

- **Python 3.12+**  
- **uv** (gestor de entornos y dependencias moderno)  
  👉 Instrucciones: https://docs.astral.sh/uv/getting-started/installation/

Recomendado:

- Visual Studio Code o Jupyter Lab

---

## 📥 2. Clonar el repositorio

```bash
git clone https://github.com/ivandres-udd/viualizacion_storytelling_proyecto_final.git

#dirigite a la carpeta del proyeto

cd viualizacion_storytelling_proyecto_final
```

## 🧪 3. Crear y activar entorno virtual con uv

### Crear entorno virtual
```bash
uv venv .venv
```

### Activar entorno
#### macOS / Linux
```bash
source .venv/bin/activate
```
#### Windows PowerShell
```bash
.venv\Scripts\Activate.ps1
```

## 📦 4. Instalar dependencias
Instala todas las dependencias declaradas en 'requirements.txt':
```bash
uv pip install -r requirements.txt
```
>recuerda que si llegas a agregar nuevas librerias, deberás actualizar el archivo
```bash
uv pip freeze > requirements.txt
```

## 📂 5. Estructura del repositorio
```bash
.
├── assets/                                      # Imágenes generadas para el storytelling
│   ├── bar_cantidad_paises.jpeg
│   ├── hitmap_evidencia_estatica.jpeg
│   ├── linear_efecto_vacuna.jpeg
│   ├── linear_evaluacion_5_paises.jpeg
│   ├── linear_evolucion_10_paises.jpeg
│   ├── linear_tendencia_mundial.jpeg
│   ├── map_evaluacion_global.jpeg
│   └── map_mortalidad_acumulada.jpeg
│
├── data/                                        # Datos utilizados en el análisis
│   └── covid-vaccination-vs-death_ratio.csv
│
├── ppt/                                         # Presentación del storytelling final
│   └── SARS-CoV-2, Pandemia, vacunas y sus efectos en la mortalidad - Reparado.pdf
│
├── src/                                         # Código fuente (notebook principal)
│   └── index_proyecto_grupal.ipynb
│
├── requirements.txt                             # Dependencias para reproducir el entorno
├── README.md                                    # Documentación principal del proyecto
└── LICENSE                                      # Licencia del repositorio

```

## 📊 6. Contenidos del análisis

El notebook desarrolla un flujo completo de análisis y storytelling basado en datos COVID-19, incluyendo:

- **Carga y limpieza de datos**
  - Unificación de datasets reales y sintéticos.
  - Conversión de tipos y manejo de valores faltantes.

- **Análisis Exploratorio (EDA)**
  - Exploración de tendencias temporales.
  - Identificación de patrones epidemiológicos.
  - Análisis descriptivo por país y región.

- **Visualizaciones**
  - Gráficas con **Matplotlib**, **Seaborn**, **Altair** y **Plotly**.
  - Heatmaps, distribuciones, series de tiempo y comparaciones multivariadas.
  - Visualizaciones interactivas para explorar correlaciones clave.

- **Storytelling**
  - Construcción de una narrativa que conecta los hallazgos con preguntas relevantes.
  - Uso de gráficos para justificar decisiones y comunicar insights.
  - Reflexión final sobre implicancias de los patrones observados.

---

## 📝 Autoría

Proyecto desarrollado por Diego Morales e Iván Peters, en el marco del curso Visualización de Datos y Storytelling – Universidad del Desarrollo.
