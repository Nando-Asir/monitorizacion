# [UNIDAD 1. PROCESOS](../README.md)
---

## Índice
### [Ir a comando PS](#1-ps)
### [Ir a comando TOP](#2-top)
### [Ir a comando HTOP](#3-htop)

---

## [1. `PS`](#índice)

- `ps` -> Muestra la información de los procesos activos.
- `ps au` -> Muestra procesos de todos los usuarios en formato extendido.

<p align="center"><img src="img/psAU.png" alt="ps" width="850" height="400"></p>

- `ps aux` -> Versión extendida que muestra todos los procesos ejecutados inclyendo los procesos del sistema, usuarios.

<p align="center"><img src="img/psAUX.png" alt="psAUX" width="850" height="400"></p>

- `ps -u <alumno>` -> Filtra y muestra solo los procesos del usuario "alumno".

<p align="center"><img src="img/psU.png" alt="psU" width="850" height="400"></p>

- `ps -eo user,pid,comm,%cpu --sort=-%cpu | head -n 6` -> Muestra los procesos del sistema con columnas personalizadas, filtrando por %cpu y las 6 primeras líneas.

<p align="center"><img src="img/ejercicio.png" alt="ejercicio" width="850" height="400"></p>

---

## [2. `TOP`](#índice)

- `top` -> Proporciona una vista en tiempo real de los procesos que más recursos consumen (CPU y memoria).

<p align="center"><img src="img/top1.png" alt="top1" width="850" height="400"></p>

- `top -b -n 3 >top.info` -> Ejecuta top en batch capturando 3 interaciones y los guarda en un archivo llamado 'top.info'.

<p align="center"><img src="img/topInfo.png" alt="topInfo" width="850" height="400"></p>

---

## [3. `HTOP`](#índice)

- `htop` -> Versión mejorada de top, con interfaz visual y funciones adicionales, como desplazamiento y filtrado de procesos.

<p align="center"><img src="img/htop.png" alt="htop" width="850" height="400"></p>

---
