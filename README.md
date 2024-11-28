# 🎵 Workshop: Evaluación de Perfiles y Melodías con Python y Google Sheets

## ✨ Descripción del Proyecto
Este repositorio contiene un proyecto que integra análisis de datos basado en la evaluación de perfiles OCEAN (Big Five) y la preferencia musical. Utilizamos herramientas de **Python** y **Google Sheets** para analizar respuestas de formularios, generar perfiles de personalidad y evaluar su alineación con calificaciones de melodías propuestas.

## 🎯 Objetivo
El objetivo es enseñar a los asistentes a:
- 🖥️ Procesar datos en tiempo real desde Google Sheets utilizando APIs.
- 📊 Realizar análisis exploratorio y modelamiento para asignar perfiles basados en rasgos OCEAN.
- 🎶 Evaluar la concordancia entre los perfiles de personalidad y las calificaciones musicales.
- 🛠️ Aplicar un pipeline analítico utilizando Python, fomentando las buenas prácticas en ciencia de datos.

## 🛠️ Pipeline del Proyecto

| **🧩 Etapa**            | **🔍 Descripción**                                                                             | **🛠️ Herramientas**     |
|-------------------------|-----------------------------------------------------------------------------------------------|--------------------------|
| **1. Sources**          | Obtención de datos desde Google Sheets mediante Google Cloud Console.                          | API Google Sheets, Python|
| **2. Procesamiento**    | Limpieza y transformación de datos en un DataFrame.                                            | Pandas                  |
| **3. Modelamiento**     | Cálculo de puntajes OCEAN, asignación de perfiles y clustering (K-Means).                      | Scikit-learn, Numpy     |
| **4. Evaluación**       | Análisis de la alineación entre perfiles y melodías calificadas, y sugerencias de mejora.       | Python, DataFrames      |
| **5. Exportación**      | Exportación de los resultados finales a Excel y publicación en un entorno compartido.          | Pandas, Google Drive    |
| **6. Visualización**    | *(Opcional)* Generación de visualizaciones para explorar los resultados obtenidos.             | Matplotlib, Seaborn     |

## 📋 Requerimientos
- **Google Cloud Console** configurado para la API de Google Sheets.
- Acceso a una cuenta de Google Drive.
- **Librerías de Python**:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `google-auth`
  - `google-auth-oauthlib`
  - `openpyxl`

## ⚙️ Configuración del Entorno
1. **Google Cloud Console**:
   - 🔐 Configura una cuenta de servicio y genera un archivo JSON con las credenciales.
   - ✅ Habilita la API de Google Sheets.
   - 📄 Comparte el archivo Google Sheet con el correo de la cuenta de servicio.

2. **Google Colab o Jupyter Notebook**:
   - 📂 Monta tu Google Drive.
   - 📦 Instala las dependencias necesarias.

## 🛠️ Instrucciones Paso a Paso

### 1. 🚀 Carga de Dependencias
Asegúrate de cargar las librerías y autenticar tu cuenta con el archivo JSON de credenciales.

### 2. 🧹 Procesamiento de Datos
1. 📥 Lee el archivo desde Google Sheets y genera un DataFrame.
2. 🔢 Calcula puntajes OCEAN y asigna perfiles.

### 3. 🎵 Evaluación de Melodías
1. 🎯 Relaciona las calificaciones de melodías con los rasgos de personalidad.
2. 📈 Genera métricas de concordancia y sugiere mejoras en los prompts.

### 4. 💾 Exportación de Resultados
Guarda los resultados en un archivo Excel compartido.

### 5. 📊 *(Opcional)* Visualización
Genera gráficos que resalten insights clave, como la distribución de perfiles o la concordancia entre melodías y perfiles.

## 🗺️ Roadmap

| 🚦 Semana | 📅 Actividad                                                                                     |
|-----------|------------------------------------------------------------------------------------------------|
| **1**     | Configuración inicial y procesamiento de datos.                                                |
| **2**     | Cálculo de puntajes y asignación de perfiles.                                                  |
| **3**     | Evaluación de melodías y ajuste de prompts.                                                    |
| **4**     | Exportación de resultados y preparación para el workshop.                                      |

## 🌟 Impacto
Este pipeline permite:
1. 🤖 Automatizar el análisis de datos de formularios.
2. ✅ Validar la alineación entre perfiles de personalidad y preferencias musicales.
3. 🔄 Iterar sobre prompts para mejorar la experiencia de personalización.

## 🤝 Contribuciones
Si tienes sugerencias o encuentras algún problema, no dudes en abrir un issue o hacer un pull request.

## 📝 Licencia
Este proyecto está disponible bajo la [Licencia MIT](LICENSE).

---

## 🔗 Enlace de la Carpeta Compartida
Accede a los resultados generados aquí: [FormResponses_Workshop.xlsx](https://docs.google.com/spreadsheets/d/1TgDjEQDSQCQg4V5TmO93_PkJb9gGmgdY/edit?usp=sharing).

---

**🎉 ¡Gracias por participar en el Workshop! 🎉**
