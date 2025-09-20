# HPC
Este repositorio está orientado al estudio y experimentación en Computación de Alto Rendimiento (HPC). El objetivo principal es implementar, analizar y comparar distintos algoritmos y estrategias de paralelización con el fin de evaluar su eficiencia, escalabilidad y rendimiento en diferentes escenarios.

# PC - Multiplicación de Matrices

Este repositorio contiene la implementación de multiplicación de matrices cuadradas en el contexto de Computación de Alto Rendimiento (HPC). Se desarrollaron tres variantes para analizar y comparar su rendimiento:

- Ejecución Secuencial en C.

- Ejecución Paralela con Hilos (pthreads).

- Ejecución Híbrida con Procesos + Hilos usando memoria compartida.

Adicionalmente, se incluye un script de automatización en Bash para ejecutar pruebas repetitivas y scripts en Python para graficar y analizar métricas como tiempo de ejecución y speedup.

# Estructura del repositorio

├── matriz_utils.c         # Funciones auxiliares (generación, memoria, temporizador)<br />
├── matriz_utils.h<br />
├── secuencial.c           # Multiplicación secuencial<br />
├── hilos.c                # Multiplicación con hilos<br />
├── procesos_hilos.c       # Multiplicación con procesos + hilos<br />
├── automatizacion.sh      # Script de ejecución y recopilación de resultados<br />
├── grafico.py             # Generación de gráficos<br />
├── tablas.py              # Generación de tablas comparativas<br />
├── resultados.csv         # Resultados de las ejecuciones<br />
└── README.md<br />

# Instalación

## Clonar el repositorio:

git clone https://github.com/TU_USUARIO/HPC_MultiplicacionMatrices.git
cd HPC_MultiplicacionMatrices


## Dar permisos de ejecución al script de automatización:

chmod +x automatizacion.sh

# Uso

Ejecutar las pruebas de forma automática con:

"`./automatizacion.sh`" 

El script realizará:

1. Compilación automática de los tres programas (secuencial, hilos y procesos+hilos).

2. Ejecución repetida de cada variante un número de veces definido (por defecto 10).

3. Variación de parámetros como tamaño de matriz, número de hilos y procesos.

4. Registro de resultados en resultados.csv.

5. Generación de gráficos y tablas comparativas.

# Temas abordados

Este proyecto se centra en conceptos de:

- HPC (High Performance Computing)

- Multiplicación de matrices

- Computación secuencial y paralelismo

- Complejidad computacional

- Hilos y procesos

- Medición de tiempos (CPU, usuario, sistema)

- Speedup y escalabilidad

# Resultados esperados

1. La versión paralela con hilos reduce significativamente el tiempo frente a la secuencial.

2. La versión procesos + hilos logra mejor escalabilidad en matrices grandes.

3. El análisis de speedup permite observar la eficiencia del paralelismo en distintos escenarios.

# Autores

Andrés Felipe Salgado Ramírez<br />
Brighitte Velez Castro<br />
Juan David Céspedes Mendoza<br />
Karen Melissa Parrra Sepulveda<br />



