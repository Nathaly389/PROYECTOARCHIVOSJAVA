# PROYECTOARCHIVOSJAVA
TRABAJO 
# Proyecto: Manipulación de Archivos y Manejo de Excepciones en Java  

## Descripción  
Este proyecto corresponde a la **Unidad 3, Tema 3.1: Manipulación de archivos y manejo de excepciones**.  
El objetivo es aplicar los principios de **programación orientada a objetos (POO)** en Java, implementando clases que permiten realizar operaciones de lectura y escritura de archivos, así como el manejo de excepciones personalizadas.  

## Clases Implementadas  
- **GestorDeArchivo**:  
  - `guardar(String nombreArchivo, String contenido)`: escribe contenido en un archivo de texto.  
  - `leer(String nombreArchivo)`: lee y devuelve el contenido del archivo línea por línea.  

- **ArchivoVacioException**:  
  - Excepción personalizada que se lanza cuando un archivo no contiene contenido.  

- **ValidadorArchivo**:  
  - `verificarNoVacio(String nombreArchivo)`: valida que el archivo no esté vacío y lanza la excepción `ArchivoVacioException` si lo está.  

- **Main**:  
  - Clase principal para probar el funcionamiento de las demás clases.  

## Ejecución del Proyecto  
1. Clonar o descargar el repositorio.  
2. Compilar las clases en la carpeta `src`:  

```bash
javac src/*.java
