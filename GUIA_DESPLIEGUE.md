# 🚀 Guía de Despliegue: MOTU Tracker en Streamlit Cloud

Esta guía te permitirá publicar tu aplicación **MOTU Tracker** en internet para que sea accesible desde tu móvil y cualquier dispositivo.

## 1. Preparación de Archivos (Ya realizado)
Hemos limpiado el proyecto de archivos temporales. Los archivos críticos para el despliegue son:
*   `original_app.py` (La aplicación principal)
*   `scrapers/` (La carpeta con los robots de búsqueda)
*   `requirements.txt` (Lista de dependencias)
*   `models.py`, `logger.py`, `circuit_breaker.py`
*   Imágenes (`.png`)

## 2. Subir a GitHub
Streamlit Cloud funciona conectándose a un repositorio de GitHub.

1.  Ve a [GitHub.com](https://github.com) e inicia sesión.
2.  Crea un **Nuevo Repositorio** (ponle nombre ej: `motu-tracker`).
3.  Selecciona "Public" (o Private si prefieres).
4.  Sube los archivos de tu carpeta `motu_project` al repositorio.
    *   Puedes usar "Upload files" desde la web de GitHub si no usas Git en consola.
    *   **IMPORTANTE**: Asegúrate de subir la carpeta `scrapers` completa con sus archivos dentro.

## 3. Conectar con Streamlit Cloud
1.  Ve a [share.streamlit.io](https://share.streamlit.io/).
2.  Inicia sesión con tu cuenta de GitHub.
3.  Pulsa en **"New app"**.
4.  Selecciona "Use existing repo".
5.  Elige tu repositorio `motu-tracker`.
6.  En "Main file path", escribe: `original_app.py`
7.  Pulsa **"Deploy!"**.

## 4. ¡Listo!
*   Streamlit instalará las librerías automáticamente.
*   En 2-3 minutos, verás tu app funcionando.
*   Copia la URL (ej: `https://motu-tracker.streamlit.app`) y envíatela por WhatsApp/Telegram.
*   Ábrela en tu móvil. ¡Ya tienes tu rastreador de bolsillo!

## ⚠️ Nota sobre DVDStoreSpain
Como DVDStoreSpain usa una estrategia de escaneo intensivo (100+ páginas), en la nube puede ser **más lento** que en tu PC local. Ten paciencia en la primera ejecución.
