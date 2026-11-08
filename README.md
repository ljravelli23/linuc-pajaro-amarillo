# LinUC Pájaro Amarillo

Simulador de algoritmos de planificación de CPU con análisis de rendimiento.
Proyecto de **Sistemas Operativos (NRC 15784)** — Universidad Católica Andrés Bello. Profesor: Ing. Gustavo Lara Jr.

## Alcance

- **Algoritmos:** FCFS, SJF no apropiativo, Round Robin con quantum configurable, Prioridades (con y sin desalojo) y SRTF como quinto algoritmo opcional.
- **Métricas:** tiempo de retorno, de espera y de respuesta por proceso; promedios y utilización de CPU.
- **Entrada:** procesos creados a mano o cargados desde un archivo CSV.
- **Resultados:** tablas, diagrama de Gantt textual y gráfico, gráficos comparativos y conclusión automática del mejor algoritmo (menor tiempo de espera promedio).

## Entorno de desarrollo

| Elemento | Selección |
|---|---|
| Sistema operativo | Ubuntu 24.04.5 LTS (x86_64) |
| Lenguaje | C++17 · GCC/G++ 13.3.0 |
| Compilación | CMake 3.28.3 |
| Interfaz y gráficos | Qt 6.4.2 (Widgets y Charts) |
| Pruebas | GoogleTest 1.14.0 |
| IDE | Visual Studio Code y Google Antigravity |

## Equipo

| Rol | Integrante |
|---|---|
| Director de Orquesta del CPU | Luigi Ravelli |
| Concertino de Interfaz y Métricas | Alfredo Gruber |
| Afinador de Algoritmos | Guillermo Salas |
| Guardián de la Partitura | Miguel Delgado |
| Crítico de Ensayos | Andrés Rosas |

## Estructura prevista

```
Core/       scheduler, process, algorithms/ (fcfs, sjf, round_robin, priority, srtf), metrics
UI/         interface, results_display
Utils/      file_handler, process_generator
tests/      conjuntos de prueba en CSV y pruebas unitarias
docs/       documentación del proyecto
```

## Documentación

- [Anteproyecto: cronograma y matriz de roles](docs/anteproyecto/)
