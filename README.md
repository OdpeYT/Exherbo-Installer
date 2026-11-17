# Exherbo-Installer
Script para instalar Exherbo de forma fácil.

# INFORMACIÓN NECESARIA
¿Qué es Exherbo? Exherbo es una distribución de Linux basada en fuentes (source-based) e independiente, con origen en Dinamarca y lanzada en 2008, diseñada principalmente para desarrolladores y usuarios avanzados que buscan un alto grado de flexibilidad y productividad. Su característica distintiva es el uso del gestor de paquetes Paludis y un modelo de desarrollo descentralizado que permite a los usuarios contribuir activamente y mezclar paquetes de fuentes oficiales o no oficiales de manera segura y determinista. 

Este script busca facilitar y automatizar la instalación; este script está basado en la guía oficial (que puedes ver en https://www.exherbo.org/docs/install-guide.html).

# QUÉ SE OCUPA
- Estar en un Live ISO de Linux Mint
- Internet
- Mucho tiempo libre
- Un disco de destino
- Un video de pantalla negra en YouTube de muchas horas para que no se bloquee la PC (opcional, pero a mí me sirve con cosas así de tardadas)

# INSTRUCCIONES
- Arranca la ISO de Linux Mint
- Descarga el `.sh` desde Releases
- Ve al directorio con `cd`
- Escribe `sudo bash exherbo_installer.sh /dev/sda` (asumamos que `sda` es tu disco de destino, pero si quieres `sdb` escribes `sudo bash exherbo_installer.sh /dev/sdb` y así)
- Escribe `SI` y le das Enter
- Pones el video en Firefox si quieres que no se bloquee
- Esperas mucho rato para que termine de instalar
- Reinicias la PC
- Escribes `user` en usuario y `1234` en contraseña
- LISTO (puedes cambiar esos datos con comandos en tu sistema, como cualquier otro Linux)

<img width="1920" height="1080" alt="Captura de pantalla_20261116_211713" src="https://github.com/user-attachments/assets/7bd3b4cc-1d3c-43ba-9e3e-eea62fdb390c" />

# LO QUE SÍ Y NO HACE:
LO QUE SÍ:
- Compila
- Automatiza tu instalación
- Te pone un kernel basado en el de Ubuntu (bueno, es el de Mint, pero sigue siendo lo que dije)
- Te deja un Exherbo funcional

LO QUE NO:
- NO instala cosas como `fastfetch`, un escritorio o eso
- NO es una ventana gráfica
- NO es magia
- Puede fallar (como cualquier script)

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3d17a7c0-ea39-49b3-b540-ffcc470c2c9f" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d47d8b27-6ea1-46e5-ae24-78f9396b80ca" />

# COSAS A CONSIDERAR
- Tiene horario America/Hermosillo (Hora Estándar del Pacífico Mexicano), o sea UTC/GMT-7
- El script está en español
- El sistema está en español
- Como esto compila mucho es muy tardado, incluso en equipos potentes
- Ocupas un Live CD de Linux Mint (el script está hecho para usarse en Linux basados en Debian, así que también podría ser Ubuntu o Debian, PERO TIENE QUE SER SÍ O SÍ BASADO EN DEBIAN, DE PREFERENCIA UBUNTU O MINT)
- El kernel que queda está basado en el de Ubuntu (es el kernel de Mint 22.3)
- La foto con `fastfetch` es porque yo lo instalé aparte, no viene con el sistema ya instalado
- Usa systemd
- No usa GRUB
