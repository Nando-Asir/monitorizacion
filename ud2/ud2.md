## [UNIDAD 2. MEMORIA, ESPACIO Y RENDIMIENTO EN DISCO](../README.md)

---

imagen

---

### Índice
### [Ir a comando FREE](#1-free)
### [Ir a comando DF](#2-df)
### [Ir a comando DU](#3-du)
### [Ir a comando IOSTAT](#4-iostat)

---

### 1. [`FREE`](#índice)

- `free` -> Muestra la cantidad de memoria física y de intercambio libre y utilizada por el sistema.
- `free -h` -> Muestra la cantidad de memoria utilizada por el sistema transformadas a unidades legibles para humanos (GB, MB, KB...).
- `free -c 3` -> Con la opción '-c 3' indicamos que repita la visualización 3 veces.

<p align="center"><img src="img/free.png" alt="free" width="850" height="400"></p>

- `free -s 3` -> Monitoriza el uso de la memoria de forma repetida, mostrado el informe cad 3 segundos.

<p align="center"><img src="img/free-S.png" alt="free-S" width="850" height="400"></p>

---

### 2. [`DF`](#índice)

- `df -h` -> Muestra la información del espacio libre y utilizado del disco con un formato legible para los humanos.

<p align="center"><img src="img/df-h.png" alt="df" width="850" height="400"></p>

---

### 3. [`DU`](#índice)

- `du -hs` -> Muestra el total del espacio utilizado por los archivos y directorios en un formato legible para los humanos.
- `du -hs /` -> Muestra el tamaño total del directorio raíz en formato legible.
- `du -hs /home` -> Muestra el tamaño total del directorio /home en formato legible.
- `du -hs /home/*` -> Muestra el total de cada directorio de un usuario dentro de /home en formato legible.

<p align="center"><img src="img/du.png" alt="du" width="850" height="400"></p>

---

### 4. [`IOSTAT`](#índice)

- `iostat -x <nombre_disco>` -> Muestra las estadísticas de entrada/salida de disco en un formato extendido de las métricas.

<p align="center"><img src="img/iostat-x_sda5.png" alt="iostat" width="850" height="400"></p>
