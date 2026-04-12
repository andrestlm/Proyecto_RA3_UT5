# Configuración de la máquina virtual

## Software utilizado
- **Aplicación:**  Oracle VM VirtualBox
- **Versión:**  7.2.6

## Configuración aplicada
- **CPU:**  2
- **RAM:**  1GB
- **Disco virtual:**  16
- **Controlador de almacenamiento:**  SATA
- **Red:** No, para comprobar la instalación desatendida  
- **Audio / vídeo / otros ajustes relevantes:**  Por defecto

## Relación con el equipo real
La CPU al ser un Intel Core 2 Duo, con dos núcleos, se le ha especificado a la maquina virtual dichos dos núcleos para simularlo de la manera más parecida posible.
El ordenador del taller contaba con un único modulo de 1GB de RAM, y eso es lo que he le he puesto, 1024MB. Aunque la velocidad de la RAM es distinta, en el ordenador del taller es DDR2, siendo bastante más lenta que en la maquina virtual.

Los periféricos no pueden ser simulados con una maquina virtual, ya que obviamente depende de que modelo de teclado y raton tienen, pero eso no es muy importante respecto al rendimiento.
Sin embargo la placa base y chipset tampoco se pueden simular y son fundamentales en como el ordenador detecta a los componentes y por ende, su rendimiento. Tampoco el controlador gráfico, ya que se esta usando el que tiene VirtualBox por defecto. Igual que los periféricos mencionados anteriormente, tampco se puede recrear el rendimiento de estos o de dispositivos integrados como USBs o dispositivos de voz y audio.
## Observación importante
La máquina virtual sirve como **banco de pruebas previo**, pero no garantiza al 100 % el mismo comportamiento que el equipo real.
Puede que algún driver en la maquina virtual ya venga configurado pero sin embargo en el ordenador real falle por cualquier motivo.
La BIOS del ordenador no se sabe si puede fallar alguna configuración en el ordenador real, ya que recrear eso en la MV es dificil.
La velocidad de arranque puede que sea bastante más lenta o la velocidad del USB puede resultar afectada por tener algo roto.
Al propio ordenador le faltan componentes como el disco duro, por tanto puede faltar cualquier otra cosa más pequeña dentro de la placa o directamente hacer conflicto con otro componente.

En general, es más facil hacer que funcionen las ISOs en una MV, ya que la máquina real puede tener problemas en el momento de usarlo o fallar en cualquier proceso del uso de dichas ISOs debido al desconocimiento de sus características.