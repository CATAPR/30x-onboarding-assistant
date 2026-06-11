# 🚀 30X AI Onboarding Assistant

## Descripción

Asistente conversacional desarrollado para apoyar el proceso de onboarding de nuevos miembros de 30X.

El sistema utiliza recuperación semántica y modelos de lenguaje para responder preguntas exclusivamente con base en la documentación interna proporcionada por la organización.

## Arquitectura

PDFs → Chunks → Embeddings → Búsqueda Semántica → Gemini → Interfaz Gradio

## Tecnologías utilizadas

* Python
* Gradio
* Google Gemini
* SentenceTransformers
* Scikit-Learn
* PyPDF

## Funcionalidades

* Respuestas basadas en documentos.
* Memoria básica de conversación.
* Escalado inteligente cuando la información no existe.
* Interfaz web accesible mediante Gradio.

## Cómo actualizar la base de conocimiento

1. Reemplazar los documentos PDF.
2. Ejecutar nuevamente el proceso de generación de embeddings.
3. Reiniciar la aplicación.

## Autor

Catalina Pulido

Prueba Técnica – Tech Volunteer 30X
