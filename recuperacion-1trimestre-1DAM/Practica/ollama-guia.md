# Ollama

Ollama es una plataforma de modelos de lenguaje grande (LLM) que te permite ejecutar y gestionar modelos de lenguaje localmente.
Se maneja a través de la línea de comandos (CLI) pero puedes integrarlo con diferentes interfaces gráficas y servidores web para facilitar su uso.

/img_ollama/`

## Instalación

Para instalar Ollama, sigue estos pasos:

1. Abre la terminal en Linux

2. Instala curl si no lo tienes instalado

3. Ejecuta el siguiente comando

```curl -fsSL https://ollama.com/install.sh | sh```

4. Una vez instalado, puedes verificar la instalación ejecutando:

```ollama version ```

## Uso básico

Puedes descargar modelos preentrenados con ```ollama pull <modelo> ```, por ejemplo:

``` ollama pull qwen2.5:0.5b ```

Descargará el modelo _qwen2.5_ de 0.5 billones de parámetros.
Para listar los modelos disponibles localmente, usa:

```ollama list ```

Si quieres ejecytar un modelo y hacerle preguntas, usa:

``` ollama run <modelo>```

## Acerca de los modelos 

Los modelos tienen diferentes capacidades y tamaños. Siguiendo el ejemplo anterior, en la página de [Ollama](https://ollama.com/) podemos encontrar diferentes versiones de _qwen2.5_:

- ```qwen2.5:0.5b``` -0.5 billones de parametros
- ```qwen2.5:1.5b ``` -1.5 billones de parámetros
- ```qwen2.5:3b``` - 3billones de parametros

Cuantos más parámetros, mayor capacidad de comprensión y generación de texto, pero también requerirá más recursos del sistema.

## Usos de ollama

Puedes usar Ollama para diversas tareas:

- Generación de texto
- Resumen de documentos
- Traducción de idiomas 
- Respuesta a preguntas
- Integración con aplicaciones personalizadas

