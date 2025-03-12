DreamPages

Sistema de recomendación de libros impulsado por NLP, que ofrece recomendaciones personalizadas basadas en descripciones detalladas de los usuarios.

## Tabla de contenidos

1. [Nombre](#Nombre)
2. [Descripción](#descripción)
3. [Arquitectura](#Arquitectura)
4. [Proceso](#Proceso)
5. [Funcionalidades](#Funcionalidades)
6. [Estado del proyecto](#EstadoDelProyecto)
7. [Agradecimientos](#Agradecimientos)

* Nombre
  
DreamPages

* Descripcíon
  
Sistema de recomendación de libros impulsado por NLP, que ofrece recomendaciones personalizadas basadas en descripciones detalladas de los usuarios. -> Alguna imagen o gif que muestre el proyecto


* Arquitectura del proyecto + imagen
  
El sistema consta de cuatro componentes principales: el frontend, el backend, el chatbot y la API de imágenes.

-Frontend (App.tsx): Es la interfaz de usuario donde se ingresan datos (descripción o título del libro), se muestran recomendaciones, detalles del libro, se interactúa en el chat y se visualizan imágenes adicionales.

-Backend (app.py): Procesa los datos ingresados por el usuario, genera recomendaciones de libros, gestiona el chat y genera imágenes adicionales. Actúa como intermediario entre el frontend, el chatbot y la API de imágenes.

-Chatbot (chatbot.py): Genera respuestas basadas en el contexto de la conversación del chat.

-API de Imágenes (TextoImagenApiPrueba2.py): Genera imágenes basadas en el título del libro proporcionado.

![flujo](https://github.com/user-attachments/assets/b8593ac7-8102-4996-a7d2-7e3dc99fab53)




* Proceso de desarrollo:

-Fuente del dataset
Diferentes Datasets provenientes de Kaggel

-Limpieza de datos (img que lo valide)
![code](https://github.com/user-attachments/assets/ec7990de-9114-400e-91c5-42c8a25fc9e0)


-Manejo excepciones/control errores
En el codigo hay "Exception" que se imprimen en el terminal indicando cual es error que ocurre

-Estadísticos (Valores, gráficos, …)
![Grafica](https://github.com/user-attachments/assets/105da860-e050-4cab-8daa-82b132d20f06)
![grafica1](https://github.com/user-attachments/assets/da1a9e5e-83d5-4057-a4ea-5daf231e288c)


* Funcionalidades extra:

Ejem 1: Integración del proyecto en una pág web
- Tecnología/Herramientas usadas …
- Arquitectura (img)

Ejem 3: Integración del proyecto en un canal WhatsApp, Discord, Telegram, Correo, …
- Tecnología/Herramientas usadas …
- Arquitectura (img)

Ejem 4: Desarrollo de interfaz gráfica de usuario
- Tecnología/Herramientas usadas …
- Arquitectura (img)

Ejem …: …
- Tecnología/Herramientas usadas …

