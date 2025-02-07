# Semáforo con Arduino y mBlock
Proyecto de semáforo implementado con Arduino y mBlock, que incluye tanto señalización digital como física mediante LEDs.

## 🚦 Descripción
Este proyecto implementa un semáforo básico utilizando Arduino y mBlock. El sistema alterna entre tres luces (roja, amarilla y verde) en intervalos específicos, mostrando la señalización tanto en LEDs físicos como en una simulación digital.

## ⏱️ Tiempos de Funcionamiento
- 🔴 Luz Roja: 2 segundos
- 🟡 Luz Amarilla: 3 segundos
- 🟢 Luz Verde: 2 segundos

## 🛠️ Componentes Necesarios
- Arduino UNO
- 3 LEDs:
  - LED Rojo
  - LED Amarillo
  - LED Verde
- 3 Resistencias de 220Ω
- Cables jumper
- Protoboard

## 📌 Conexiones
- LED Rojo → Pin 13 (con resistencia 220Ω)
- LED Amarillo → Pin 12 (con resistencia 220Ω)
- LED Verde → Pin 11 (con resistencia 220Ω)
- Todos los cátodos de los LEDs → GND

## 💻 Software Necesario
- [mBlock](https://mblock.makeblock.com/en-us/)
- [Arduino IDE](https://www.arduino.cc/en/software)

## 🔧 Instalación
1. Clonar el repositorio:
```bash
git clone [URL-del-repositorio]
```

2. Abrir mBlock y cargar el archivo del proyecto
3. Conectar el Arduino vía USB
4. Actualizar el firmware si es necesario
5. Cargar el programa al Arduino

## 📝 Instrucciones de Uso
1. Realizar las conexiones según el diagrama proporcionado
2. Abrir el proyecto en mBlock
3. Conectar el Arduino
4. Presionar la bandera verde para iniciar
5. El semáforo comenzará su ciclo automáticamente

## 🔗 Enlaces
- [Simulación en Tinkercad](https://www.tinkercad.com/things/c3Gl08uXsUM-semaforo)
- [Documentación de mBlock](https://www.mblock.cc/doc/en/)
- [Guía de Arduino](https://www.arduino.cc/en/Guide)

## 📊 Diagrama de Tiempos
```
Rojo     ███████░░░░░░░░░░░░░
Amarillo ░░░░░░░████████░░░░░
Verde    ░░░░░░░░░░░░░░███████
         0s  2s  3s  5s  7s
```

## 🎯 Características
- Control de LEDs físicos
- Simulación digital en pantalla
- Temporización precisa
- Ciclo continuo automático

## 🚀 Configuración de mBlock
1. Activar modo Arduino
2. Agregar extensión de Arduino
3. Configurar puerto COM
4. Verificar actualización de firmware

## ⚠️ Notas Importantes
- Verificar la polaridad correcta de los LEDs
- Asegurar el uso de resistencias apropiadas
- Comprobar las conexiones a GND
- Mantener el cable USB conectado durante la programación

## 🤝 Contribuciones
Las contribuciones son bienvenidas. Para cambios importantes:
1. Hacer Fork del repositorio
2. Crear una nueva rama
3. Realizar los cambios
4. Enviar un Pull Request

## Licencia
Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## Autor
[Pedro Carranza](https://github.com/draexx)
