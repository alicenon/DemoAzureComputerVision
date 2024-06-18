# DemoAzureComputerVision


[](https://drive.google.com/file/d/1wL0svYuD9TY_kjZ-_yyN0kkAXNzWS95z/view?usp=drive_link)
![computervision](https://cdn.discordapp.com/attachments/732694522110148721/1252648348452786176/computervisionAlice_1.jpg?ex=6672fb2f&is=6671a9af&hm=e54443a0e7710bb82bca32abb42dd0750ea1e25827165e3ab522bc6436797e7b&)

## Explicación de la arquitectura a pequeños rasgos


1.   **Instalación** y configuración de bibliotecas: Se instala la biblioteca `azure-cognitiveservices-vision-computervision` y se importan los módulos necesarios.
2.   **Autenticación**: Se configuran las credenciales necesarias para autenticar el cliente de Computer Vision.
3.   **Análisis de imágenes**:

     `analyze_image()` : Analiza una imagen especificada por una URL y extrae etiquetas con una confianza superior al 75%.\
     `analyze_image_by_domain()`: Analiza imágenes para dominios específicos como lugares famosos.\
     `describe_image()`: Obtiene descripciones de texto para una imagen.
     
Para ver el código completo y ejemplos de uso, consulta el archivo 
[DemoAzureComputerVision.ipynb](https://github.com/alicenon/DemoAzureComputerVision/blob/main/DemoAzureComputerVision.ipynb)

