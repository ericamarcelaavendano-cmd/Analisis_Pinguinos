# 🐧 Análisis de Pingüinos

Proyecto de ciencia de datos para analizar un conjunto de datos sobre pingüinos.
Este repositorio contiene la configuración del entorno de trabajo para que cualquier
integrante del equipo pueda replicarlo fácilmente.

##  Librerías utilizadas

- **pandas**: manipulación de datos
- **matplotlib**: visualización
- **seaborn**: visualizaciones estadísticas

##  Configuración del entorno

### 1. Clonar el repositorio

```bash
git clone <URL-del-repositorio>
cd semana_11/analisis_pinguinos
```

### 2. Crear el entorno virtual

```bash
python -m venv .venv
```

### 3. Activar el entorno virtual

**Windows (PowerShell):**
```bash
.venv\Scripts\Activate.ps1
```

**Windows (CMD):**
```bash
.venv\Scripts\activate
```

**Mac / Linux:**
```bash
source .venv/bin/activate
```

Cuando el entorno esté activo, verás `(.venv)` al inicio de la terminal.

### 4. Instalar las dependencias

```bash
pip install -r requirements.txt
```

### 5. Verificar la instalación

```bash
python analisis.py
```

Si no aparece ningún error, el entorno está listo. 🎉

## Estructura del proyecto

```
analisis_pinguinos/
├── .venv/              # Entorno virtual (no se sube al repositorio)
├── .gitignore
├── analisis.py
├── README.md
└── requirements.txt
```

## Autora

Erica Avendaño - Análisis y Desarrollo de Software, CESDE