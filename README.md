# Laboratorio 9 - Inteligencia Artificial
## CC3045 - Semestre I - 2024

### Descripción
Este laboratorio se enfoca en el estudio y aplicación de los Modelos Ocultos de Markov (Hidden Markov Models, HMM) y el algoritmo Forward-Backward. El objetivo es comprender los conceptos teóricos detrás de los HMM y implementar el algoritmo Forward-Backward para predecir el estado del tiempo en un modelo meteorológico simplificado.

### Tareas
- **Task 1 - Teoría:**
  - Responder de forma clara y concisa las siguientes preguntas:
    1. Diferencia entre Modelos de Markov y Hidden Markov Models.
    2. Investigar qué son los factorial HMM (Hidden Markov Models).
    3. Especificar en sus propias palabras el algoritmo Forward-Backward para HMM.
    4. Explicar por qué es necesario el paso de Backward en el algoritmo Forward-Backward.
  - Las respuestas pueden ser subidas en un PDF o dentro del mismo Jupyter Notebook.

- **Task 2 - Algoritmo Forward-Backward en HMM:**
  - Implementar el algoritmo Forward-Backward para un modelo meteorológico representado por un HMM con dos estados: "Soleado" y "Lluvioso".
  - Definir los parámetros del modelo oculto de Markov (HMM), incluyendo estados, observaciones, probabilidades iniciales, probabilidades de transición y probabilidades de emisión.
  - Crear una instancia de la clase HMM con los parámetros definidos.
  - Generar una secuencia de observaciones utilizando el método `generate_sequence` (opcional pero útil para realizar pruebas).
  - Utilizar el método `forward` para calcular las probabilidades directas.
  - Utilizar el método `backward` para calcular las probabilidades hacia atrás.
  - Utilizar el método `compute_state_probabilities` para calcular las probabilidades de estar en cada estado en cada paso de tiempo dada la secuencia observada.
  - Imprimir o analizar las probabilidades calculadas según sea necesario.

### Entregables
1. Link al repositorio de los integrantes del grupo.
   - Subir también el código a Canvas por temas de Acreditación.

### Evaluación
1. [1 pts.] Task 1 (0.25 pts cada pregunta)
2. [4 pts.] Task 2 - Implementación de algoritmo
Total: 5 pts.

## Requisitos Previos (Usamos CONDA !! :D)

- Miniconda instalado en su sistema. Si no tiene Miniconda, puede descargarlo desde [aquí](https://docs.conda.io/en/latest/miniconda.html).

## Configuración del Entorno

Siga estos pasos para configurar el entorno Conda necesario para ejecutar el notebook:

1. **Clonar el Repositorio**

Primero, clone el repositorio a su máquina local usando Git:

```bash
git clone https://github.com/AndresQuinto5/IA_LAB08.git
cd IA_LAB08
```

### Crear el Entorno Conda
Cree un entorno Conda utilizando el archivo environment.yml incluido en el repositorio. Esto instalará todas las dependencias necesarias.

```
conda env create -f environment.yml
```

### Activar el entorno

```
conda activate nombre_del_entorno
```

#### Ejecutar el Jupyter Notebook

Con el entorno activado, inicie Jupyter Notebook o JupyterLab:

```
jupyter notebook
# o
jupyter lab
```

### Autores
- [Andres Quinto - 18288](https://github.com/AndresQuinto5)
- [Marlon Hernández - 15177](https://github.com/ivanhez)