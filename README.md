# movvvvedorDeObjetos
movedor de objetos en 3d y replicador - con salida spout
Hecho y exportado en VVVV Gamma 5.2


# Descargar 

**https://github.com/lisandroperalta/movvvvedorDeObjetos/releases/**

## Modelos 3d para probar en

**https://github.com/lisandroperalta/movvvvedorDeObjetos/tree/main/modelos3DParaProbar**


![Captura de pantalla 2023-12-18 220537](https://github.com/lisandroperalta/movvvvedorDeObjetos/assets/23583735/0d27d0bd-0800-4c9b-896d-d039c7dce7fd)


*Nota:* se puede hacer pan/tilt/orbit/zoom con el mouse. Presionando R se reestablece la camara


# Nueva version: 004
-para evitar crasheos, no se puede usar objeto 3d si antes no se carga uno 
-checkbox para usar la camara con el mouse o no
-clonado en x e y 
-velocidad de giro ahora permite no girar el objeto
-spread de giro define cada cuantas repeticiones se defasa un objeto
-las luces se mueven lentamente (para lograr que iluminen desde todos los angulos posibles)


![version 002](https://github.com/lisandroperalta/movvvvedorDeObjetos/assets/23583735/c54d4ab8-b81f-4cc3-80b3-617c49d10508)



# Nueva version: 003
-Agregado más opciones de movimiento
-Agregado de opcion de usar textura o no

![version 002](https://github.com/lisandroperalta/movvvvedorDeObjetos/assets/23583735/c54d4ab8-b81f-4cc3-80b3-617c49d10508)


# Descargar 

**https://github.com/lisandroperalta/movvvvedorDeObjetos/releases/**

## Modelos 3d para probar en

**https://github.com/lisandroperalta/movvvvedorDeObjetos/tree/main/modelos3DParaProbar**





---------------------------------------------------

**Si no funciona, se puede probar instalando las siguientes dependencias (extraido de https://thegraybook.vvvv.org/reference/hde/exporting.html#dependencies )**


**Dependencies**
If your application is referencing VL.Stride, make sure the target PC also has the following dependencies installed:

Microsoft Visual C++ Redistributables 2013 
https://aka.ms/highdpimfc2013x64enu

Microsoft Visual C++ Redistributables 2015 https://aka.ms/vs/17/release/vc_redist.x64.exe

.NET6 SDK (For FileTexture and FileModel nodes to work) https://dotnet.microsoft.com/en-us/download/dotnet/6.0

---------------------------


### IMPORTANTE
Probando, con @jpupper encontramos que puede ser que ande instalando además, este otro sdk

https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/sdk-6.0.403-windows-x64-installer

*En todo caso, con instalando el vvvv gamma funciona, aunque no lo use*
https://teamcity.vvvv.org/guestAuth/app/rest/builds/id:37342/artifacts/content/vvvv_gamma_5.2_setup.exe
