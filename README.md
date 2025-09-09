# Proceso de Arranque y Encendido de una Computadora
Este documento resume lo aprendido en el curso **Fundamentos de Ingeniería de Software de Platzi**, sobre cómo se inicia un computador al presionar el botón de encendido.  
El proceso es fundamental porque determina si el sistema podrá iniciar correctamente y hacerlo de forma segura.

## Etapas principales

### 1. BIOS (Basic Input/Output System)  
- Inicializa y prueba los componentes básicos.  
- Permite la comunicación entre el sistema operativo y los dispositivos.  

### 2. POST (Power-On Self Test)  
- Verifica que memoria, teclado, video y otros componentes funcionen correctamente.  
- Si ocurre un error, muestra mensajes o señales sonoras.  

### 3. Bootloader  
- Programa que transfiere el control al sistema operativo.  
- Ejemplos: GRUB (Linux), Windows Boot Manager.  

## Detalles del proceso
- El usuario enciende la computadora.  
- La energía eléctrica viaja desde la fuente hacia los circuitos, iniciando el proceso automático.  
- El BIOS despierta y ejecuta el POST.  
- Si el POST es exitoso, el bootloader carga el sistema operativo en memoria.  
- El sistema operativo toma el control y habilita la interacción con el usuario.  


## Importancia en Ciberseguridad
Comprender este flujo permite identificar puntos de vulnerabilidad:  
- Malware en el sector de arranque (MBR, bootkits).  
- Manipulación del BIOS/UEFI.  
- Seguridad en el arranque mediante UEFI y Secure Boot.  


## Conclusión
El arranque de un computador es mucho más que una pantalla negra con texto:  
es la base que permite que todo el sistema funcione. Conocerlo es esencial para entender cómo trabajan nuestros dispositivos y cómo asegurar su integridad en el contexto de la **ciberseguridad**.

![rjywryjhwr](https://github.com/user-attachments/assets/f64c613e-7bb6-4270-910a-7aed2128e9cf)
