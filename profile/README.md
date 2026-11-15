<div align="center">

# MOOVIA

### Velocity-Based Training con datos que puedes comprobar.

Sensor inalámbrico que muestrea la IMU a **1000 Hz** y calcula en cada repetición **VMP, velocidad pico, ROM, tempo y conteo**. Estamos en fase de prototipo: estas métricas todavía no están validadas contra un sistema de referencia (encoder lineal o cámara de alta velocidad), y por eso exportamos la señal cruda para que se puedan contrastar.

[🌐 moovia.app](https://moovia.app) · [Instagram](https://www.instagram.com/moovia.app) · [LinkedIn](https://www.linkedin.com/company/moovia-app-) · [YouTube](https://www.youtube.com/channel/UCbLA7HbfGZRzJMIHT53AArw)

</div>

---

## Qué es MOOVIA

Un wearable que se coloca en la manga de la barra y captura el movimiento a 1000 Hz. Al terminar el set, tu móvil muestra las métricas de cada repetición — velocidad, ROM, tempo y conteo — con datos crudos exportables en JSON.

## Ecosistema

| Repo | Qué es |
|---|---|
| **MOOVIA_Code_App** | Software: apps de análisis (móvil + web), fusión de sensores y conteo de repeticiones. |
| **moovia-wbz351-firmware** | Firmware del sensor (WBZ351 / PIC32CX-BZ3, BLE, IMU ICM-42688-P @ 1000 Hz). |
| **moovia-hardware** | Diseño hardware: PCB KiCad (v1 fabricada + v2) y datasheets. |
| **MOOVIA-WEB** | Web comercial (Next.js + Firebase). |

## En colaboración con

**Barcelona Activa.**

---

<div align="center">

Hecho por atletas, para atletas.

© MOOVIA

</div>
