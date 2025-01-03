# Proyecto Implementación del Modelo Llama para la Interpretación Automática de LENSEGUA

El proposito de este módulo es de poder entrena una LLM, en este caso LLAMA, para que esta pueda interpretar una traducción de la lengua de señas de Guatemala, LENSEGUA, a oraciones o frases completas, coherentes y consias. Basado en un sata set de datos basado en esta misma lengua, con sus grámatica respctiva, el propósito final sería realizar traducciones a cualquier traducción realizada para generar las oraciones.

## Instrucciones de Instalación
IMPORTANTE: Si no se tiene un GPU para poder cargar localmente los modelos, se necesita utilizar una plataforma de nube o virtual para realizar esto. En este, se recomienda Google Colab con varios de sus diferentes GPUs disponibles.

### Librerías a instalar
- accelerate==0.26.0 
- peft==0.9.0 -
- bitsandbytes==0.40.2 
- transformers==4.37.2 
- trl==0.4.7 
- datasets==2.14.6 
- fire==0.5.0 
- lime
- evaluate
- huggingface_hub

### Contraseña para acceder a HuggingFace y LLaMa
- HF_TOKEN = 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

## Comandos para instalar proyecto
- Utilizar Colab con recursos. Seleccionar una GPY con suficiente espacio para trabajar, al menos 6 de RAM de GPU.

### Dataset de datos a utilizar
- Datos creados para entrenar modelo originalmente
- Datos utilizados en ambas LLaMA y GPT-3.5

### Ejecución de NoteBook
- Siempre instalar todo al principio. Para ver el proceso de entrenamiento, seguir adelante. Para ver el funcionamiento del programa final utilizada, saltar hasta Prubeas y Funcionamiento.

## Demo
[Link para el Demo](https://github.com/Roberto-VC/PG-2024-20441/blob/main/Implementaci%C3%B3n%20del%20Modelo%20Llama%20para%20la%20Interpretaci%C3%B3n%20Autom%C3%A1tica%20de%20LENSEGUA/demo/demo.mp4)

## Informe
[Link para el Informe](https://github.com/Roberto-VC/PG-2024-20441/blob/main/Implementaci%C3%B3n%20del%20Modelo%20Llama%20para%20la%20Interpretaci%C3%B3n%20Autom%C3%A1tica%20de%20LENSEGUA/docs/Informe.pdf)

## Google Colab
[Link al Google Colab](https://colab.research.google.com/drive/1VbR9pUMkIEgJlFTuWFnjTiIqU9Pmf-HM)


