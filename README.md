# 🛡️ QuickUIForge

**QuickUIForge** es una herramienta de escritorio diseñada para desarrolladores que buscan proteger su propiedad intelectual. Facilita la ofuscación de scripts de Python utilizando el motor de **Cytron**, permitiendo procesar archivos individuales o proyectos completos (carpetas) a través de una interfaz gráfica intuitiva y moderna.

---

## ✨ Características Principales

* **Interfaz Gráfica (GUI):** Gestión visual completa, eliminando la necesidad de comandos complejos en la terminal.
* **Procesamiento por Lotes:** Capacidad para seleccionar directorios raíz y ofuscar todos los archivos `.py` de forma recursiva.
* **Integración con Cytron:** Aprovecha la robustez del motor Cytron para transformar código legible en scripts protegidos.
* **Compatibilidad Multiplataforma:** Diseñado para funcionar en entornos donde Python y sus librerías de GUI estén presentes.

---

## 🛠️ Tecnologías Utilizadas

* **Lenguaje:** [Python 3.x](https://www.python.org/)
* **Motor de Ofuscación:** Cytron
* **Interfaz:** PyQt6 / PySide6 (Arquitectura de escritorio)
* **Gestión de Archivos:** Librerías nativas para manejo de rutas y directorios.

---

## 🚀 Instalación y Configuración

Sigue estos pasos para preparar tu entorno de desarrollo:

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/tu-usuario/OfuzPyCytron.git](https://github.com/tu-usuario/QuickUIForge.git)
    cd QuickUIForge
    ```

2.  **Crear un entorno virtual (Recomendado):**
    ```bash
    python -m venv venv
    # En Windows:
    venv\Scripts\activate
    ```

3.  **Instalar dependencias:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Ejecutar la aplicación:**
    ```bash
    python main.py
    ```

---

## 📖 Guía de Uso

1.  **Selección de Entrada:** Haz clic en el botón de búsqueda para elegir un script específico o una carpeta que contenga tu proyecto de Python.
2.  **Ruta de Salida:** El documento o los documentos se agregaran en la misma ruta donde se encuentras los documentos originales.
3.  **Procesar:** Presiona el botón **"Compilar y ofuscar"**. La aplicación procesará cada archivo y te mantendrá informado mediante una barra de estado o logs en tiempo real.
4.  **Finalización:** Una vez terminado, tus archivos estarán listos en la carpeta de destino para su distribución segura.

---

## 📂 Estructura del Proyecto

```text
QuickUIForge/
├── main.py              # Punto de entrada de la aplicación
└── requirements.txt     # Listado de dependencias del proyecto
```
---

## 🤝 Contribuciones
¡Las contribuciones son bienvenidas! Si deseas mejorar la lógica de ofuscación o la interfaz:

1. Realiza un Fork del proyecto.
2. Crea una rama para tu mejora (git checkout -b feature/MejoraIncreible).
3. Haz un Commit de tus cambios (git commit -m 'Añadir mejora').
4. Realiza un Push a la rama (git push origin feature/MejoraIncreible).
5. Abre un Pull Request.

## 🧾 Licencia
Este proyecto está bajo la Licencia MIT. Esto permite el uso personal y comercial, siempre que se incluya el aviso de copyright original. Para más detalles, consulta el archivo LICENSE en este repositorio.
