# 🌐 hostScan.sh

`hostScan.sh` es un script en Bash diseñado para descubrir hosts activos dentro de una subred específica mediante un escaneo basado en `ping`.

## ⚙️ Características

- Escanea direcciones IP del **192.168.1.1 al 192.168.1.254** (puede modificarse fácilmente).
- Usa el comando `ping` con `timeout` para verificar si un host está activo.
- Ejecuta cada prueba en **paralelo** para mejorar la velocidad del escaneo.
- Maneja la señal `Ctrl+C` mostrando un mensaje de salida amigable.

## 🧪 Uso

```bash
chmod +x hostScan.sh
./hostScan.sh
```

> 💡 *Puedes modificar el rango o la subred cambiando `192.168.1.$i` dentro del script.*

## 📦 Requisitos

- Bash
- Comandos: `ping`, `timeout`

## ⚠️ Advertencia

Este script debe usarse únicamente con fines **educativos** o en redes bajo tu control o con autorización explícita. El uso indebido puede ser considerado ilegal según tu legislación local.
