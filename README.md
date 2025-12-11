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

## 📊 6. Resumen del Análisis y Visualizaciones


### 🧭 1. Contexto inicial: La pandemia y sus primeras consecuencias

* Se observa una alta mortalidad global durante los primeros meses de pandemia, especialmente en potencias como Estados Unidos, India, Brasil y Rusia.

* El gráfico de evolución de mortalidad para los 10 países con mayor mortalidad absoluta evidencia peaks dramáticos entre fines de 2020 y mediados de 2021.

* La disponibilidad de vacunas aún era limitada, lo que explica por qué la mayoría de los países no superaba el 10% de vacunación los primeros tres meses.

### 🌍 2. Comparativo global: primeros 3 meses vs últimos 3 meses
#### 2.1 Mortalidad acumulada

* En los primeros 3 meses, el mundo enfrenta tasas de mortalidad extremadamente elevadas.

* En los últimos 3 meses, muchos países presentan reducciones significativas, aunque otros (EE.UU., Perú, Rusia) mantienen niveles altos.

#### 2.2 Vacunación global

* Países con vacunación temprana: Estados Unidos, Reino Unido, Chile, Emiratos Árabes.

* Rezago marcado en África y Medio Oriente debido a dificultades logísticas y acceso limitado.

### 📈 3. Tendencia global: Vacunación vs Mortalidad

* Aumento sostenido de vacunación desde enero 2021.

* Caída abrupta de la mortalidad promedio global, pasando de ~6.7 muertes/millón a cerca de 2.5 muertes/millón.

* Este gráfico representa el punto de quiebre del storytelling: cuando más del 25% de la población mundial se vacunó, la curva de mortalidad cambió radicalmente.

### 🇺🇸🇧🇷🇮🇳 4. Caso Países Top 3: Efecto directo de la vacunación

(Estados Unidos – Brasil – India)

En los tres países se observa:

* Aumento pronunciado de vacunación durante 2021.

* Disminución significativa de las muertes una vez alcanzados niveles medianos de inmunización.

* La relación visual destaca que el impacto no es inmediato, pero sí consistente en el mediano plazo.

### 🔬 5. Evidencia estadística: Correlación entre variables

* Fuerte correlación positiva entre total_vaccinations, people_vaccinated y population.

* Correlación negativa moderada entre ratio de vacunación y nuevas muertes.

* A mayor vacunación, menor mortalidad.

### 📉 6. Distribución inicial: ¿Qué tan vacunado estaba el mundo?

* En febrero 2021 la enorme mayoría de países tenía menos del 10% de vacunación.

* La falta de disponibilidad global fue clave en la persistencia de altas tasas de mortalidad iniciales.

### 🧩 7. Conclusiones integradas del análisis

* La vacunación masiva representó el mayor factor de reducción de mortalidad global.

* El impacto fue visible tanto a nivel país como a nivel mundial, especialmente después del segundo trimestre de 2021.

* Persisten diferencias marcadas entre regiones debido a factores logísticos, económicos y políticos.

La vacuna no lo fue todo:
* El autocuidado y restricciones siguieron siendo determinantes en los periodos intermedios.

* La inmunidad de rebaño comenzó a lograrse entre 25%–40% de la población inmunizada, coherente con la caída global de muertes.

### 🧠 8. Síntesis para storytelling (ABT Framework)
#### AND – Contexto

* El mundo sufre una ola inicial de mortalidad explosiva y avanza lentamente en distribución de vacunas.

#### BUT – Punto de quiebre

* Pero a mediados de 2021, cuando la vacunación toma ritmo global, las tasas de mortalidad comienzan a caer de manera evidente y consistente.

#### THEREFORE – Conclusión

* Por lo tanto, la evidencia muestra que la rápida inmunización global fue clave para frenar la mortalidad, aunque la desigualdad en el acceso retrasó los beneficios para grandes regiones del planeta.


---

## 📝 Autoría

Proyecto desarrollado por Diego Morales e Iván Peters, en el marco del curso Visualización de Datos y Storytelling – Universidad del Desarrollo.
