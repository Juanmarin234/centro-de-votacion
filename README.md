##  Requisitos



Antes de ejecutar el programa, asegúrate de tener Python 3 instalado y ejecutar:



```bash

pip install pandas matplotlib

```



##  Cómo ejecutar



1. Clona el repositorio o descarga los archivos.

2. Abre una terminal en la carpeta del proyecto.

3. Ejecuta:



```bash

Python simulador_electoral_modificado.py

```



##  Archivos planos requeridos



### votantes.csv

### resultados.json

##  Funcionalidades principales



- Registro de jurados por salón, mesa y botón.

- Carga de votantes desde `votantes.csv`.

- Registro de asistencia (hora máxima 4:00 PM).

- Carga de resultados (`.csv` o `.json`).

- Búsqueda de votantes y jurados por cédula.

- Estadísticas por salón y votación usando `pandas`.

- Gráficos automáticos con `matplotlib`.



## 💾 Guardado y carga



- Puedes guardar la estructura del centro de votación y cargarla luego desde un archivo `.json`.
