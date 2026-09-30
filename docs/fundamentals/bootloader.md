# Bootloader

## Que es un bootloader?
El bootloader es en si codigo que ejecuta antes del sistema operativo y su funcion principal es preparar el hardware, con todo ello el bootloader decide que imagen arrancar, la verifica y transfiere el control al sistema operativo.
## Que ocurre antes de que android arranque?
El recorrido que hace en si al precionar el boton de encendido seria este:

Energia  
    &Downarrow;  
Procesador sale del reset  
    &Downarrow;  
Boot ROM  
    &Downarrow;  
Bootloader  
    &Downarrow;  
Verified Boot  
    &Downarrow;  
Kernel Linix  
    &Downarrow;  
init  
    &Downarrow;  
Servicios de Android  
    &Downarrow;  
Listo para usar  

## Que significa que el bootloader este locked?
Significa que el proveedor o distribuidor del dispositivo lo tiene bloqueado, hay tipos de bloqueos por lo que vi con mi pixel 6, esta el locker y el locket(unlockeable), cuando esta locked creo que es cuando no puedes modificarlo, pondre de ejemplo los iphone, que no se puede modificar el sistema de esos celulares.

## Por que necesitamos desbloquearlo para instalar otro sistema operativo?
Para no tener los filtros y bloqueos de eso, supongo que aparte de que las empresas lo ocupan para su beneficio tambien es parte de la proteccion, saco esa deduccion pensando en grapheneOS que dice que al intalarlo es recomendable volver a hacerle locked, lo cual me hace deducir que tambien es parte la proteccion contra ciertos tipos de malware.