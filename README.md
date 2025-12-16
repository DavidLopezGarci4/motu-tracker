# ⚔️ MOTU Tracker

**MOTU Tracker** es una aplicación diseñada para los coleccionistas de *Masters of the Universe*. Esta herramienta permite monitorizar en tiempo real el stock y precios de figuras en diversas tiendas online de España.

![MOTU Tracker Screenshot](Masters_buscador.png)

## 🚀 Características

*   **Búsqueda Multi-tienda**: Rastrea automáticamente productos en tiendas como *Kidinn*, *ActionToys*, *Pixelatoy*, y más.
*   **Interfaz Temática**: Disfruta de una experiencia visual inmersiva con temática de He-Man, incluyendo una barra de progreso personalizada con la Espada de Poder.
*   **Filtrado Inteligente**: Elimina resultados irrelevantes para mostrarte solo lo que realmente buscas.
*   **Logs Detallados**: Sistema de registro para monitorizar el proceso de búsqueda y depurar errores.

## 🛠️ Instalación y Uso

1.  **Clonar el repositorio**:
    ```bash
    git clone https://github.com/DavidLopezGarci4/motu-tracker.git
    cd motu-tracker
    ```

2.  **Instalar dependencias**:
    Se recomienda usar un entorno virtual.
    ```bash
    pip install -r requirements.txt
    ```

3.  **Ejecutar la aplicación**:
    ```bash
    streamlit run original_app.py
    ```

## 📂 Estructura del Proyecto

*   `original_app.py`: Archivo principal de la aplicación Streamlit.
*   `scrapers/`: Contiene los módulos de scraping para cada tienda.
*   `models.py`: Definición de modelos de datos.
*   `GUIA_DESPLIEGUE.md`: Instrucciones para desplegar la app en Streamlit Cloud.

## ⚠️ Estado del Proyecto
Este proyecto es una copia de seguridad del estado funcional ("Backup: Preservar estado actual del proyecto").
