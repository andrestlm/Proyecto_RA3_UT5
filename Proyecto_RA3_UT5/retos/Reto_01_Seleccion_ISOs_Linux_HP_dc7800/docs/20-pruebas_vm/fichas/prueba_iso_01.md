# Prueba ISO 01

## 1. Datos generales
- **Nombre de la ISO probada:**  Puppy Linux, Bookworm
- **Fecha:**  12 de abril, 2026
- **Software de virtualización:**  VirtualBox

## 2. Configuración de la VM
- **CPU asignada:**  2
- **RAM asignada:**  1 GB
- **Disco virtual:**  16 GB
- **Tipo de arranque configurado:**  BIOS Legacy
- **Otras opciones relevantes:**  Controlador USB 2.0, SIN aceleración de gráficos

## 3. Resultado del arranque
El sistema se ha iniciado sin problema, mostrando diferentes opciones en el GRUB de la ISO, pudiendo seleccionar la más adecuada para lo que lo queremos usar. En este caso es la primera opcion. Tras eso, inicia el entorno grafico y una ventana de setup para poner el idioma y la hora. Con esto el sistema está listo para usar, y cualquier cosa que guardemos se guardará en el USB. A la hora de apagar, para que se guarde todo, hay que guardar la sesión.

## 4. Resultado del instalador
Aunque este sistema se usa desde un USB, se puede instalar.
En mi caso estoy en la versión Bookworm de Debian, y el proceso cambia respecto a otras versiones más modernas y antiguas. Hay que ir al a la opcion de instalar en la parte de setup dentro del menú, crear las particiones con Gparted (una de /boot en FAT32 y otra de / en ext4). Luego instalar los archivos de puppy en dicha opción, usando de fuente los archivos actuales del sistema, y por ultimo instalar el boot en la parte de boot en la partición FAT32. No es un proceso dificil pero hay que tener ciertos conocimientos. Despues guardar en la partición con la / en ext4 y reiniciar, quitando el USB.
## 5. Resultado final
Tras iniciarse se puede ver que el disco USB no se ve abajo a la derecha y sale el disco principal. Tambien se puede ver el almacenamiento en el visor de recursos de la derecha. Al abrir las particiones se puede ver la jerarquía de directorios común en boot y en la raíz.

## 6. Capturas relacionadas
![Captura BIOS](../../../assets/img/20-vm_iso_01/iso-01-GRUB.png)
![Captura arranque](assets/img/20-vm_iso_01/iso-01-arranque.png)
![Captura instalador](assets/img/20-vm_iso_01/iso-01-instalador.png)
![Captura resultado](assets/img/20-vm_iso_01/iso-01-resultado.png)
![Captura resultado 2](assets/img/20-vm_iso_01/iso-01-resultado-2.png)

## 7. Valoración
Es la principal y  mejor opción para este ordenador del taller. Porque no hace falta disco duro y porque es de los que menos consume, sin perder funcionalidades. Quitando el inconveniente de guardar cada vez que apagas. Es muy buena opción.
