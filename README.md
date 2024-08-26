# Proyecto en Ciencia de Datos 2024-Otoño
Repositorio con las notas de clase del curso de Proyecto de Ciencia de Datos Otoño 2024. 

Este repositorio contiene todos los materiales y notebooks necesarios para los tres módulos de este curso. 

Cada módulo está organizado en carpetas separadas, con los contenidos correspondientes.

## Gestión de Dependencias

Este proyecto permite la gestión de dependencias de dos maneras: usando [Poetry](https://python-poetry.org/) o con un archivo `requirements.txt`.

### Opción 1: Usando Poetry

Poetry es una herramienta de gestión de dependencias y empaquetado para Python. Para instalar las dependencias del proyecto con Poetry, ejecuta el siguiente comando:

```bash
poetry install
```

### Opción 2: Usando requirements.txt

Si prefieres usar `pip` y un archivo `requirements.txt`, puedes instalar las dependencias con el siguiente comando:

```bash
pip install -r requirements.txt
```

## Estructura del Curso

### `Módulo 1.` **Fundamentos de Python.**

Este módulo cubre los conceptos básicos de Python y las herramientas esenciales para el desarrollo y gestión de proyectos en Python.

- **Introducción a Python**: Conceptos básicos del lenguaje y primeros pasos.
- **¿Qué es Git? - Git & GitHub**: Fundamentos de control de versiones y uso de GitHub para la colaboración en proyectos.
- **Ambientes Virtuales (Virtual Environment)**: Creación y manejo de entornos virtuales en Python.
- **Sistemas de recomendación personalizados/NLP (LLMs)**: Introducción a los modelos de lenguaje y sistemas de recomendación personalizados.
- **Introducción a la Interfaz de Programación de Aplicaciones (API)**: Conceptos básicos sobre APIs y su uso en proyectos de desarrollo.

### `Módulo 2.`  **Introducción a MLOps y Diseño de Sistemas de Machine Learning**

Este módulo explora los fundamentos de MLOps y cómo diseñar sistemas de Machine Learning listos para producción.

- **Fundamentos de MLOps**:
  - ¿Por qué hacer MLOps? Beneficios y desafíos.
  - Niveles de madurez de MLOps.
  - Introducción al diseño de sistemas de Machine Learning para producción.
  
- **Diseño de Sistemas de Machine Learning**:
  - Principios de diseño para aplicaciones escalables de ML.
  - Diferencias entre despliegue batch y online.

### `Módulo 3.`  **Desplegando, Monitoreando y Gestionando Modelos de Machine Learning Escalables**

Este módulo se enfoca en el despliegue, monitoreo y gestión de modelos de Machine Learning en un entorno escalable.

- **Introducción al despliegue de modelos como servicio (Model as a Service)**:
  - Uso de Docker y APIs para la creación de servicios web.
  - Despliegue de modelos escalables utilizando AWS.
  
- **Tracking, Registro y Monitoreo de Modelos**:
  - Introducción a MLflow para tracking de experimentos y Model Registry.
  - Monitoreo de modelos en producción.
  - Orquestación de flujos de trabajo con Mage.
  - Buenas prácticas para asegurar la calidad y escalabilidad de los modelos en producción.
