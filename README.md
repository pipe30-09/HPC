# HPC
Este repositorio está orientado al estudio y experimentación en Computación de Alto Rendimiento (HPC). El objetivo principal es implementar, analizar y comparar distintos algoritmos y estrategias de paralelización con el fin de evaluar su eficiencia, escalabilidad y rendimiento en diferentes escenarios.

# PC - Multiplicación de Matrices

Este repositorio contiene la implementación de multiplicación de matrices cuadradas en el contexto de Computación de Alto Rendimiento (HPC). Se desarrollaron tres variantes para analizar y comparar su rendimiento:

✅ Ejecución Secuencial en C.

✅ Ejecución Paralela con Hilos (pthreads).

✅ Ejecución Híbrida con Procesos + Hilos usando memoria compartida.

Adicionalmente, se incluye un script de automatización en Bash para ejecutar pruebas repetitivas y scripts en Python para graficar y analizar métricas como tiempo de ejecución y speedup.

# Estructura del repositorio

├── matriz_utils.c         # Funciones auxiliares (generación, memoria, temporizador)
├── matriz_utils.h
├── secuencial.c           # Multiplicación secuencial
├── hilos.c                # Multiplicación con hilos
├── procesos_hilos.c       # Multiplicación con procesos + hilos
├── automatizacion.sh      # Script de ejecución y recopilación de resultados
├── grafico.py             # Generación de gráficos
├── tablas.py              # Generación de tablas comparativas
├── resultados.csv         # Resultados de las ejecuciones
└── README.md

