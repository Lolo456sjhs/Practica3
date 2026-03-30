# Practica 3 , Actividad 7 — Control con Arduino Esplora y visualización en ESP32

Este repositorio contiene una práctica donde un **Arduino Esplora** funciona como control y envía comandos por comunicación serial a un **ESP32**, el cual dibuja una escena sencilla tipo pseudo-3D en una pantalla **Nokia 5110**.

## Archivos
- `esp32_juego.ino` — Sketch principal del ESP32 que recibe comandos desde el Esplora y renderiza la escena en la pantalla Nokia 5110.
- `esplora_control.ino` — Sketch del Arduino Esplora que lee el joystick y botones para enviarlos como comandos al ESP32.




