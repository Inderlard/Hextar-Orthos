# Hextar-Orthos

Impresora 3D con sistema multicabezal independiente a partir de la Ender 3

![](https://github.com/Inderlard/Hextar-Orthos/blob/main/Media/Hextar%20Orthos.png?raw=true)
![](https://github.com/Inderlard/Hextar-Orthos/blob/main/Media/Cambio%20Ocabezal.gif?raw=true)

## Actualizaciones previas

Ademas del material esencial para realizar esta actualizacion se requiere doble Eje Z

## Informacion sobre el firmware

Para realizar esta actualizacion se ha realizado un cambio en el pinout de la MKS Monster 8 en el firmware [Marlin](https://github.com/MarlinFirmware/Marlin)

El PW det esta en el Y+
El runout esta en el Z+
El autoshutdown esta puenteado en el Y- solo usando alimentacion V y G (NO USA EL S)
Los HOST ACTION COMAND estan activos y habilitan la opcion de apagar la impresora desde la misma.

El X2 se situa en el E0, 4º driver, en adelante los demas extrusores (Solo apto para 2 extrusores sin Z dual driver)
