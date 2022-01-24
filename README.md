# Bety-Byte - Movimiento Cocacola/Cocacola RedZone

## Tabla de Contenidos

- [Bety-Byte - Movimiento Cocacola/Cocacola RedZone](#bety-byte---movimiento-cocacolacocacola-redzone)
  - [Tabla de Contenidos](#tabla-de-contenidos)
  - [Lo que sabemos](#lo-que-sabemos)
  - [Juegos](#juegos)
  - [Ficheros/Assets Internos (.pak)](#ficherosassets-internos-pak)
  - [Comportamientos](#comportamientos)
  - [URL Conocidas](#url-conocidas)
  - [Videos](#videos)
  - [Proyectos de Cocacola similares internacionalmente](#proyectos-de-cocacola-similares-internacionalmente)

## Lo que sabemos

El Movimient

BetyByte 

## Juegos

La mayoria de juegos de BetyByte usan un "Motor" llamado "Clima" derivado del Motor Software Libre, Irrlicht Engine (zlib License), los unicos juegos que aparentan ser diferentes son SnowBattle y SummerBattle (que de momento se consideran perdidos).  

La mayoria de las llamadas relacionadas con Irrlicht se situan en gui.dll

Segun parece usan un sistema de metadatos del acceso directo para saber que juego arrancar en vez de usar parametros o ficheros default (como lo hace HL2 o Frostbite Engine).

Los parametros de configuracion (de servidor) se ubican en regedit de windows: HKEY_LOCAL_MACHINE\Software\Wow6432Node\BetyByte (En un Sistema de 64 Bits, probablemente sea muy similar quitando el Wow6432Node)

los servidores originales se ubicaban en `213.4.106.94` y `213.4.106.95`. cambiado a `download.cocacola.es` y El Puerto usado para las actualizaciones el 85.  
Todos ellos no responden hoy en dia.

|Juegos| Codename | Enlace | Contenido |   |
|---|---|---|---|---|
| Futbol11  | Futbol11  | [Spanish](https://web.archive.org/web/*/http://www.cocacola.es:80/cab/futbol11.exe), [Dinamarca](https://web.archive.org/web/*/http://www.redzone.dk:80/uploads/cab/InstaladorBetyByte.Futbol11.DK.exe) | Hay varios ficheros de Assets incluyendo vestidor, tiene pinta de poder arrancar  |   |
| Emparejados  | Arena  |  [Spanish](https://web.archive.org/web/*/http://www.cocacola.es:80/cab/instaladorempareja-2.exe), [Dinamarca](https://web.archive.org/web/*/http://www.redzone.dk:80/uploads/cab/InstaladorBetyByte.Arena.DK.exe) | Hay varios ficheros de Assets incluyendo vestidor, tiene pinta de poder arrancar  |
| Universal/The Cocacola Hotel |   | <https://web.archive.org/web/*/http://www.cocacola.es:80/cab/InstaladorUniversal.exe>  |  Hay varios ficheros de Assets incluyendo vestidor, tiene pinta de poder arrancar |
| RoadRider | ???? | [Dinamarca](https://web.archive.org/web/*/http://www.redzone.dk:80/uploads/cab/InstaladorBetyByte.RoadRaider.DK.exe) | Posibilidad que esten mas o menos actualizados dependiendo del instalador |
| Vestidor | vestidor | Se incluye con todos los juegos de cocacola | Posibilidad que esten mas o menos actualizados dependiendo del instalador |
| SnowBattle | ???? | [Spanish (2003)](https://web.archive.org/web/*/http://download.cocacola.es:80/snowbattle/Updater_es.exe), [Spanish](https://web.archive.org/web/*/http://download.cocacola.es:80/descargas/snowbattle/updater.exe), [Dinamarca](http://download.cocacola.es/snowbattle/Updater_dk.exe), [Niue? (NU)](https://web.archive.org/web/*/http://download.cocacola.es:80/snowbattle/Updater_nu.exe) | Es un Updater Stub. Se requiere de alguien con los ficheros instalados,  |
| SummerBattle | ???? | [Spanish](https://web.archive.org/web/*/http://download.cocacola.es:80/descargas/summerbattle/updater.exe)| Es un Updater Stub. Se requiere de alguien con los ficheros instalados |

???
https://web.archive.org/web/*/http://www.redzone.dk:80/uploads/cab/instaladorbetybyteuk.cab

## Ficheros/Assets Internos (.pak)

De momento, No se ha podido extraer/desencriptado ningun fichero, los ficheros de assets estan formato ".pak" que los contenidos no corresponden a ningun formato conocido y no hay un claro delimitador de datos entre fichero y fichero, asi que probablemente los offsets y inicio de secuencia esten en el header del fichero (cuales ya muestran los nombres de los ficheros dentro de .pak) pero probablemente habra que saber el metodo de desencriptacion.

## Comportamientos

El Updater.exe puede eliminar clima.exe, el update devuelve como exitcode con un 1.  
Para mas precaucion, usar un ejecutable como que devuelva un 0 con nombre de updater.exe.

## URL Conocidas

cocacola.es - Obviamente web Oficial  
download.cocacola.es - CDN de Cocacola/BetyByte (Todos los enlaces de Snowbattle internacional redireccionan a aqui)  
www.redzone.dk - Version de Dinamarca del Movimiento Cocacola

## Videos

[SnowBattle](https://www.youtube.com/watch?v=v23GkhJE-A0) resubido por mi, el autor original lo puso en privado.  
[RedZone - MiniCD](https://www.youtube.com/watch?v=V3ocJnNix6s) Este Video que muestra un MiniCD es el contenido rescatado mas reciente a pesar de no estar archivado de Archive.org  
[Spot de Dinamarca de RedZone](https://www.youtube.com/watch?v=WFKF2NrEew8) - Equivalente al movimiento cocacola.  

## Proyectos de Cocacola similares internacionalmente

[MyCoke](https://en.wikipedia.org/wiki/MyCoke) - Alternativa Estadounidense parecida a Habbo Hotel pero usando el Motor de Sulake  
Ciudad Konec-t - La Alternativa mexicana mas proxima a Habbo Hotel