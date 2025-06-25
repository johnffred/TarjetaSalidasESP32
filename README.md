# 🔌 Proyecto: Tarjeta de salidas con ESP32

Este proyecto consiste en el diseño y desarrollo de una tarjeta electrónica basada en ESP32, que permite controlar múltiples salidas mediante relés de estado sólido, visualizar información en una pantalla LCD y recibir entradas desde botones físicos. Todo el diseño de hardware se ha realizado en **KiCad**.

---

## 📦 Componentes principales

| Componente             | Descripción                                      |
|------------------------|--------------------------------------------------|
| ESP32-WROOM-32D        | Microcontrolador principal                       |
| Relés G3MB-202P        | Relés de estado sólido para controlar salidas    |
| Pantalla LCD 16x2 I2C  | Interfaz de usuario                              |
| Botones de entrada     | Para control manual de salidas                   |
| Fuente IRM-05-5        | Fuente de 5 V conmutada                           |
| CH340C                 | Conversor USB a serial para programar el ESP32   |
| USB Tipo A             | Conexión de energía o programación               |

---

## 📐 Diseño en KiCad

- `esquematico.kicad_sch`: esquema eléctrico completo
- `pcb_layout.kicad_pcb`: diseño de la placa (en desarrollo)
- `BOM.csv`: lista de materiales (opcional)

---

## 💻 Programación

La programación se realiza en Arduino IDE o PlatformIO.  
Funcionalidades previstas:
- Activación de salidas mediante botones
- Visualización del estado de salidas en la pantalla LCD
- Control de pines y lógica de relés

📌 Asignación de pines:

| Función     | Pin ESP32 |
|-------------|-----------|
| Relé 1      | GPIO25    |
| Relé 2      | GPIO26    |
| Relé 3      | GPIO27    |
| Relé 4      | GPIO32    |
| Botones     | GPIO34, 35, 36, 39 |
| LCD I2C SDA | GPIO21    |
| LCD I2C SCL | GPIO22    |

---

## 📋 Estado del proyecto

| Tarea                          | Estado     |
|-------------------------------|------------|
| Diseño de esquema             | ✅ Completo |
| Diseño PCB                    | ⏳ En progreso |
| Programación básica           | ⏳ En pruebas |
| Pruebas de relés              | 🔜 Por hacer |
| Documentación en GitHub       | ✅ Lista    |

---

## 🧑‍💻 Autor

**John Franco**  
📅 Junio 2025  
🔗 Licencia: MIT
