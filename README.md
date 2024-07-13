# Ollama PDF Chatbot

[Versión en Español](#versión-en-español)

This project implements a chatbot capable of interacting with PDF documents. The chatbot is built using `Streamlit` and various natural language processing libraries. It allows users to upload PDF files and ask questions about the content of those files.

## Features

- Upload and process PDF documents
- Ask questions about the content of the PDFs
- Get accurate and context-aware responses
- User-friendly interface using Streamlit

## Requirements

To run this project, you'll need to have Python installed along with the required libraries. The necessary dependencies are listed in the `requirements.txt` file.

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/ggranadosp/ollama_pdf_chatbot.git
    cd ollama_pdf_chatbot
    ```

2. **Create a Virtual Environment**:
    ```bash
    python -m venv env
    source env/bin/activate   # On Windows use: env\Scripts\activate
    ```

3. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the Application**:
    ```bash
    python app.py
    ```

2. **Interact with the Chatbot**:
    - Open your web browser and navigate to the URL provided by Streamlit (usually `http://localhost:8501`).
    - Upload a PDF file using the provided interface.
    - Ask questions about the content of the PDF.

## File Structure

- `app.py`: Main application script for running the Streamlit interface.
- `requirements.txt`: List of dependencies required to run the project.
- `rag.py`: Contains the logic for reading and extracting information from PDF files.

## Dependencies

The project relies on the following Python libraries:

- `streamlit==1.10.0`
- `streamlit-chat==0.1.1`
- `langchain_community==0.0.1`
- `PyPDF2==3.0.1`
- `chromadb==0.5.3`
- `fastapi`
- `httpx>=0.27.0`
- `langchain==0.0.188`
- `fastembed==0.3.1`

These dependencies are automatically installed when you run `pip install -r requirements.txt`.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Contact

For any questions or suggestions, please contact [ggranadosp](https://github.com/ggranadosp).

---

## Versión en Español

[Back to English Version](#ollama-pdf-chatbot)

Este proyecto implementa un chatbot capaz de interactuar con documentos PDF. El chatbot está construido usando `Streamlit` y varias bibliotecas de procesamiento de lenguaje natural. Permite a los usuarios subir archivos PDF y hacer preguntas sobre el contenido de esos archivos.

### Características

- Subir y procesar documentos PDF
- Hacer preguntas sobre el contenido de los PDFs
- Obtener respuestas precisas y contextualmente adecuadas
- Interfaz fácil de usar mediante Streamlit

### Requisitos

Para ejecutar este proyecto, necesitarás tener Python instalado junto con las bibliotecas necesarias. Las dependencias necesarias están listadas en el archivo `requirements.txt`.

### Instalación

1. **Clonar el Repositorio**:
    ```bash
    git clone https://github.com/ggranadosp/ollama_pdf_chatbot.git
    cd ollama_pdf_chatbot
    ```

2. **Crear un Entorno Virtual**:
    ```bash
    python -m venv env
    source env/bin/activate   # En Windows usa: env\Scripts\activate
    ```

3. **Instalar Dependencias**:
    ```bash
    pip install -r requirements.txt
    ```

### Uso

1. **Ejecutar la Aplicación**:
    ```bash
    python app.py
    ```

2. **Interactuar con el Chatbot**:
    - Abre tu navegador web y navega a la URL proporcionada por Streamlit (generalmente `http://localhost:8501`).
    - Sube un archivo PDF usando la interfaz proporcionada.
    - Haz preguntas sobre el contenido del PDF.

### Estructura de Archivos

- `app.py`: Script principal de la aplicación para ejecutar la interfaz de Streamlit.
- `requirements.txt`: Lista de dependencias necesarias para ejecutar el proyecto.
- `rag.py`: Contiene la lógica para leer y extraer información de archivos PDF.

### Dependencias

El proyecto depende de las siguientes bibliotecas de Python:

- `streamlit==1.10.0`
- `streamlit-chat==0.1.1`
- `langchain_community==0.0.1`
- `PyPDF2==3.0.1`
- `chromadb==0.5.3`
- `fastapi`
- `httpx>=0.27.0`
- `langchain==0.0.188`
- `fastembed==0.3.1`

Estas dependencias se instalan automáticamente cuando ejecutas `pip install -r requirements.txt`.

### Contribuir

Si deseas contribuir a este proyecto, por favor haz un fork del repositorio y envía un pull request. Para cambios importantes, por favor abre un issue primero para discutir lo que te gustaría cambiar.

### Licencia

Este proyecto es de código abierto y está disponible bajo la [Licencia MIT](LICENSE).

### Contacto

Para cualquier pregunta o sugerencia, por favor contacta a [ggranadosp](https://github.com/ggranadosp).
