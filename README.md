# 🎬 Movies Dataset Template

Plantilla de aplicación web desarrollada con **Streamlit** para visualizar y explorar conjuntos de datos de películas.

El proyecto sirve como ejemplo de referencia para la creación de aplicaciones analíticas ligeras utilizando Python y Streamlit, proporcionando una estructura sencilla que puede reutilizarse como base para proyectos de visualización de datos.

[![Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://movies-dataset-template.streamlit.app/)

---

## Descripción

Esta aplicación demuestra cómo construir una interfaz web interactiva utilizando Streamlit para explorar y analizar datos tabulares.

La arquitectura está diseñada para ser minimalista y fácil de extender, permitiendo:

* Visualización de conjuntos de datos.
* Exploración interactiva de información.
* Creación rápida de prototipos analíticos.
* Despliegue sencillo en entornos locales o en la nube.

---

## Arquitectura

El proyecto sigue una arquitectura simple basada en Streamlit.

```text
movies-dataset-template/
│
├── streamlit_app.py
├── requirements.txt
└── README.md
```

### Componentes principales

| Archivo            | Descripción                       |
| ------------------ | --------------------------------- |
| `streamlit_app.py` | Punto de entrada de la aplicación |
| `requirements.txt` | Dependencias del proyecto         |
| `README.md`        | Documentación del repositorio     |

---

## Características Técnicas

### Interfaz Reactiva

La aplicación utiliza el modelo de ejecución reactivo de Streamlit, donde la interfaz se actualiza automáticamente cuando cambian los datos o las interacciones del usuario.

### Visualización de Datos

Permite mostrar información estructurada mediante componentes nativos de Streamlit, tales como:

```python
st.dataframe()
st.table()
st.metric()
st.chart()
st.selectbox()
```

### Desarrollo Rápido

Streamlit elimina la necesidad de desarrollar:

* Frontend en JavaScript.
* APIs REST dedicadas.
* Frameworks adicionales para visualización.

Todo el flujo se implementa utilizando únicamente Python.

---

## Requisitos

### Software

* Python 3.9 o superior
* pip

### Dependencias

Las dependencias del proyecto se encuentran definidas en:

```text
requirements.txt
```

---

## Instalación

### 1. Clonar el repositorio

```bash
git clone <repositorio>
cd movies-dataset-template
```

### 2. Crear un entorno virtual (recomendado)

**Windows**

```bash
python -m venv .venv
.venv\Scripts\activate
```

**Linux/macOS**

```bash
python -m venv .venv
source .venv/bin/activate
```

### 3. Instalar dependencias

```bash
pip install -r requirements.txt
```

---

## Ejecución

Iniciar la aplicación localmente:

```bash
streamlit run streamlit_app.py
```

Una vez iniciada, Streamlit mostrará una URL similar a:

```text
http://localhost:8501
```

Abrir dicha dirección en el navegador para acceder a la aplicación.

---

## Desarrollo

Durante el desarrollo, Streamlit detecta automáticamente los cambios en el código fuente y recarga la aplicación sin necesidad de reiniciarla manualmente.

Esta característica permite iteraciones rápidas y mejora la productividad durante la construcción de prototipos.

---

## Despliegue

La aplicación puede desplegarse fácilmente en:

* Streamlit Community Cloud
* Docker
* Kubernetes
* Servidores Linux
* Plataformas cloud (AWS, Azure, Google Cloud)

El único requisito es disponer de Python y las dependencias especificadas en `requirements.txt`.

---

## Tecnologías Utilizadas

* Python
* Streamlit
* Pandas
* NumPy
* Bibliotecas de visualización compatibles con Streamlit

---

## Casos de Uso

Esta plantilla puede utilizarse como punto de partida para:

* Dashboards analíticos.
* Aplicaciones de Business Intelligence.
* Exploración de datasets.
* Visualización de métricas.
* Prototipos de ciencia de datos.
* Herramientas internas de análisis.

---

## Ventajas de la Arquitectura

* Implementación sencilla.
* Bajo número de dependencias.
* Curva de aprendizaje reducida.
* Desarrollo rápido.
* Fácil mantenimiento.
* Despliegue simplificado.
* Escalabilidad adecuada para aplicaciones analíticas ligeras y medianas.

---

## Licencia

Este proyecto puede adaptarse y reutilizarse como plantilla base para aplicaciones desarrolladas con Streamlit.
