# [UNIDAD 1. PROCESOS](../README.md)

---

## 1. `PS`

- `ps` -> Muestra la información de los procesos activos
- `ps au` -> Muestra procesos de todos los usuarios en formato extendido

<p align="center"><img src="img/psAU.png" alt="ps" width="850" height="400"></p>

- `ps aux` -> Versión extendida que muestra todos los procesos ejecutados inclyendo los procesos del sistema, usuarios

<p align="center"><img src="img/psAUX.png" alt="psAUX" width="850" height="400"></p>

- `ps -u <alumno>` -> Filtra y muestra solo los procesos del usuario "alumno"

<p align="center"><img src="img/psU.png" alt="psU" width="850" height="400"></p>

- `ps -eo user,pid,comm,%cpu --sort=-%cpu | head -n 6` -> Muestra los procesos del sistema con columnas personalizadas, filtrando por %cpu y las 6 primeras líneas

<p align="center"><img src="img/ejercicio.png" alt="ejercicio" width="850" height="400"></p>
