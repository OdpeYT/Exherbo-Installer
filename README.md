# Exherbo-Installer
Script para instalar Exherbo de forma facil.

# INFORMACION NECESARIA
¿Qué es exherbo? Exherbo es una distribución de Linux basada en fuentes (source-based) e independiente, con origen en Dinamarca y lanzada en 2008, diseñada principalmente para desarrolladores y usuarios avanzados que buscan un alto grado de flexibilidad y productividad.  Su característica distintiva es el uso del gestor de paquetes Paludis y un modelo de desarrollo descentralizado que permite a los usuarios contribuir activamente y mezclar paquetes de fuentes oficiales o no oficiales de manera segura y determinista. 

Este script busca facilitar y automatizar la instalacion, este script esta basado en la guia oficial (que puedes ver en https://www.exherbo.org/docs/install-guide.html)

# QUE SE OCUPA
- Estar en un live iso de Linux Mint
- Internet
- Mucho tiempo libre
- Un disco de destino
- Un video de pantalla negra en yt de muchas horas para que no se bloquee la pc (opcional, pero a mi me sirve con cosas asi de tardadas)

# INSTRUCCIONES
- Arranca la ISO de linux mint
- Descarga el .sh desde releases
- Ve al directorio con cd
- Escribe sudo bash exherbo_installer.sh /dev/Sda (asumamos que sda es tu disco de destino, pero si quieres sdb escribes sudo bash exherbo_installer.sh /dev/Sdb y asi)
- Escribe SI y le das enter
- Pones el video en firefox si quieres que no se bloquee
- Esperas mucho rato pa que termine de instalar
- Reinicias la pc
- Escribes user en usuario y 1234 en contraseña
- LISTO (puedes cambiar esos datos con comandos en tu sistema, como cualquier otro linux)

<img width="1920" height="1080" alt="Captura de pantalla_20261116_211713" src="https://github.com/user-attachments/assets/7bd3b4cc-1d3c-43ba-9e3e-eea62fdb390c" />
# LO QUE SI Y NO HACE:
LO QUE SI:
- Compila
- automatiza tu instalacion
- te pone un kernel basado en el de ubuntu (bueno, es el de mint pero sigue siendo lo que dije)
- te deja un exherbo funcional

LO QUE NO:
- NO instala cosas como fastfetch, un escritorio o eso
- NO es una ventana grafica
- NO es magia
- Puede fallar (como cualquier script)

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3d17a7c0-ea39-49b3-b540-ffcc470c2c9f" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d47d8b27-6ea1-46e5-ae24-78f9396b80ca" />

# COSAS A CONSIDERAR
- Tiene Horario America/Hermosillo (Hora Estándar del Pacífico Mexicano), o sea UTC/GMT-7
- El script está en español
- El sistema está en español
- Como esto compila mucho es muy tardado, incluso en equipos potentes
- Ocupas un live cd de linux mint (el script esta hecho pa usarse en linux's basados en debian, asi que tambien podria ser ubuntu o debian, PERO TIENE QUE SER SI O SI BASADO EN DEBIAN, DE PREFERENCIA UBUNTU O MINT)
- El kernel que queda está basado en el de ubuntu (es el kernel de mint 22.3)
- La foto con fastfetch es porque yo lo instalé a parte, no viene con el sistema ya instalado
- Usa SystemD
- No usa GRUB
