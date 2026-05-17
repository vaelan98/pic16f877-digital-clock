# 🕐 Digital Clock with Alarm — PIC16F877

> Embedded systems project — B.Sc. Mechatronics Engineering  
> Universidad del Valle de Guatemala
---
##
## 🇬🇧 English

### Overview

A fully functional digital clock built on the **PIC16F877 microcontroller**, featuring real-time display of time and date, and a programmable alarm system — all implemented in embedded C with no external clock modules.

### Features

- 🕐 **Real-time clock** — hours, minutes, seconds
- 📅 **Full date display** — day, month, year
- ⏰ **Programmable alarm** — set and trigger custom alarm times
- 💡 **Live display** — output via LCD / 7-segment display
- ⚙️ **Built entirely on PIC16F877** — no external RTC module

### Tech Stack

| Component | Detail |
|---|---|
| Microcontroller | PIC16F877 |
| Language | Embedded C |
| IDE | MPLAB X |
| Display | LCD / 7-segment |
| Modules used | Timer0, Timer1, ADC, USART |

### How It Works

```
PIC16F877
├── Timer0 / Timer1 → timekeeping (seconds, minutes, hours)
├── GPIO → display output (LCD / 7-segment)
├── Interrupt → alarm trigger
└── User input → set time, date & alarm
```

---

## 🇪🇸 Español

### Descripción

Reloj digital completamente funcional construido sobre el **microcontrolador PIC16F877**, con visualización en tiempo real de hora y fecha completa, y sistema de alarma programable — todo implementado en C embebido sin módulos RTC externos.

### Funcionalidades

- 🕐 **Reloj en tiempo real** — horas, minutos, segundos
- 📅 **Fecha completa** — día, mes, año
- ⏰ **Alarma programable** — configuración y activación de alarma personalizada
- 💡 **Visualización en vivo** — salida por pantalla LCD / display 7 segmentos
- ⚙️ **100% en PIC16F877** — sin módulo RTC externo

### Stack Tecnológico

- **Microcontrolador:** PIC16F877
- **Lenguaje:** C embebido
- **IDE:** MPLAB X
- **Display:** LCD / 7 segmentos
- **Módulos usados:** Timer0, Timer1, ADC, USART

---

## 👤 Author · Autor

**Juan Gerardo González Morales**  
Mechatronics Engineer | INCAE MBA & MAIT  
🔗 [linkedin.com/in/juan-gonzalez98](https://linkedin.com/in/juan-gonzalez98)  
💻 [github.com/vaelan98](https://github.com/vaelan98)
