# Ficha · Intento de instalación 1

## 1. Datos básicos
- ISO utilizada: Puppy Linux
- Fecha y hora aproximada: Viernes 17 a última hora (20:05-21:00)
- Puesto dentro del plan: principal

## 2. Arranque
- ¿Se seleccionó la ISO desde Ventoy?: Sí
- ¿La ISO arrancó correctamente?: Sí
- Evidencia: ![Evidencia](../../../assets/img/20-intento_iso_01/puppy_arranque.png "Evidencia de que arrancó")
- ![Evidencia](../../../assets/img/20-intento_iso_01/puppy_arranque_2.png "Evidencia de que arrancó")
## 3. Instalación
- ¿Se llegó al instalador?: Sí, se puede llegar, pero no fue necesario.
  
- Tipo de instalación elegido: Ninguna, es un sistema operativo que se caracteriza por no necesitar que se instale, y como en ese momento nuestro PC no tenia disco duro, no lo instalamos. Pero en caso de instalarlo en una instalación manual.
 
- Esquema de particionado usado: No usamos, pero en caso de usarlas hay que crear una de /boot en FAT23 y otra de la partición raíz en ext4. La partición raiz contiene copiada la informacion del usb, tal cual se copia y pega, y el boot lo instala el propio instalador.
  
- Pasos principales realizados(TODOS LOS RELEVANTES):
  1. Abrir instalador
  2. Crear particiones
  3. Darles formato
  4. Instalar desde el USB
  5. Reiniciar

## 4. Resultado del intento
- ¿La instalación finalizó correctamente?: Se pudo usar sin instalar correctamente
- ¿El sistema arrancó después?: Sí
- Estado final: éxito

## 5. Problemas encontrados
- Problema 1: No teníamos la hora correcta, ya que la pila CMOS estaba gastada
- Problema 2: No teníamos disco duro
- Problema 3: La pantalla no podía ser conectada por VGA

## 6. Soluciones aplicadas
- Solución 1: Cambiar la hora y fecha desde la BIOS con las flechas y el tab
- Solución 2: Luego le pusimos uno, aunque parecía no funcionar
- Solución 3: Usamos VDI

## 7. Decisión tomada
Como está ISO no hace falta instalarla, el próximo día usaremos ISOS que si podemos instalar para ver como seria el proceso. Es funcional, pero necesita del USB y de que la RAM esté en buen estado.

## 8. Evidencias
- Captura de arranque: ![Evidencia](../../../assets/img/20-intento_iso_01/puppy_arranque.png "Evidencia de que arrancó")
- Captura del instalador: ![Evidencia](../../../assets/img/20-intento_iso_01/puppy_arranque_2.png "Evidencia de que arrancó")
- Captura del resultado final o del error: ![Evidencia](../../../assets/img/20-intento_iso_01/puppy_resultado.png "Evidencia de que arrancó")
