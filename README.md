# PuenteDualshokexplo

PuenteDualshokexplo es una aplicación de código abierto que permite conectar mandos de PlayStation 4 a una PC mediante Wi-Fi o USB.

Actualmente, el mando probado oficialmente es el DualShock 4 de PS4. El uso con otros tipos de mando no está garantizado.

## Descargas

Puedes descargar la versión más reciente desde la sección **Releases**.

- `PuenteMando.apk`: aplicación Android.
- `ReceptorMando.exe`: programa receptor para Windows.
- `PuenteMando.zip`: código o archivos de la aplicación Android.
- `puente.ds4.zip`: código o archivos relacionados con el soporte de DualShock 4.

## Requisitos

Antes de ejecutar el proyecto desde Python debes instalar:

### Windows

Descarga e instala **ViGEMBus**, componente necesario para crear mandos virtuales.

### Python

Instala las dependencias necesarias:

```bash
pip install vgamepad
pip install cryptography
pip install psutil
```

Se recomienda usar Python 3.10 o una versión posterior.

## Uso

1. Instala el APK en tu teléfono Android.
2. Instala ViGEMBus en tu PC.
3. Ejecuta el receptor correspondiente en Windows.
4. Conecta el mando DualShock 4 por USB o asegúrate de que el teléfono y la PC estén en la misma red Wi-Fi.
5. Sigue las instrucciones de la aplicación para realizar la conexión.

## Advertencia

Esta versión es experimental. El instalador o el ejecutable pueden activar avisos de Windows o antivirus porque todavía no está firmado digitalmente.

## Problemas y recomendaciones

Si encuentras errores al conectar el mando, abre un Issue e incluye:

- Versión de Windows y Android.
- Modelo del mando.
- Método de conexión: Wi-Fi o USB.
- Descripción del problema.
- Capturas de pantalla o mensajes de error.

Si pruebas otro tipo de mando, también puedes comentar si funciona y qué modelo utilizaste.

<img width="220" height="162" alt="67-6767" src="https://github.com/user-attachments/assets/bfb7501e-c2d9-40b0-bc17-8a03af210e79" />

