# Bety-Byte - Movimiento Cocacola/Cocacola RedZone

## Tabla de Contenidos

- [Bety-Byte - Movimiento Cocacola/Cocacola RedZone](#bety-byte---movimiento-cocacolacocacola-redzone)
  - [Tabla de Contenidos](#tabla-de-contenidos)
  - [Lo que sabemos](#lo-que-sabemos)
  - [Juegos](#juegos)
  - [Ficheros/Assets Internos (.pak)](#ficherosassets-internos-pak)
  - [Comportamientos](#comportamientos)
  - [URL Conocidas](#url-conocidas)
  - [Articulos & Referencias](#articulos--referencias)
  - [Videos](#videos)
  - [Proyectos de Cocacola similares internacionalmente](#proyectos-de-cocacola-similares-internacionalmente)

## Lo que sabemos

El Movimiento Coca-Cola (De aqui para adelante denominado MovCola) nacio en 2003 y fue exportado como "redzone"  como varios paises como Dinamarca, Niue, Filandia y Noruega.

BetyByte es la prinicipal desarrolladora de los juegos y CMS de MovCola (denominado Bety-Byte como redzone-games), Incluso dejando nombre de directorio en español en los CMS no españoles.

## Juegos

La mayoria de juegos de BetyByte usan un "Motor" llamado "Clima" derivado del Motor Software Libre, Irrlicht Engine (zlib License), los unicos juegos que aparentan ser diferentes son SnowBattle y SummerBattle (que de momento se consideran perdidos).  

La mayoria de las llamadas relacionadas con Irrlicht se situan en gui.dll

Segun parece usan un sistema de metadatos del acceso directo para saber que juego arrancar en vez de usar parametros o ficheros default (como lo hace HL2 o Frostbite Engine),  

El codigo de los juegos estan en ficheros .ifc (realmente son librerias win32 renombrados)

Los parametros de configuracion (de servidor) se ubican en regedit de windows: HKEY_LOCAL_MACHINE\Software\Wow6432Node\BetyByte (En un Sistema de 64 Bits, probablemente sea muy similar quitando el Wow6432Node)

Los servidores usaban un sistema basado en Red Hat (Segun ciertas entrevistas de la epoca)

los servidores originales se ubicaban en `213.4.106.94` y `213.4.106.95`. cambiado a `download.cocacola.es` y el puerto usado para las actualizaciones el 85.  
Todos ellos no responden hoy en dia.

|Juegos| Codename | Enlace | Contenido |   |
|---|---|---|---|---|
| Futbol11  | futbol11  | [Spanish](https://web.archive.org/web/*/http://www.cocacola.es:80/cab/futbol11.exe), [Dinamarca](https://web.archive.org/web/*/http://www.redzone.dk:80/uploads/cab/InstaladorBetyByte.Futbol11.DK.exe) | Hay varios ficheros de Assets incluyendo vestidor, tiene pinta de poder arrancar  |   |
| Tunnel Of Love  | charisma  |  |   |   |
| Emparejados  | arena  |  [Spanish](https://web.archive.org/web/*/http://www.cocacola.es:80/cab/instaladorempareja-2.exe), [Dinamarca](https://web.archive.org/web/*/http://www.redzone.dk:80/uploads/cab/InstaladorBetyByte.Arena.DK.exe), [Filandes](https://web.archive.org/web/*/http://www.redzone.fi:80/uploads/cab/InstaladorBetyByte.Arena.FI.exe) | Hay varios ficheros de Assets incluyendo vestidor, tiene pinta de poder arrancar  |
| Universal/The Cocacola Hotel | universal  | [Spanish](https://web.archive.org/web/*/http://www.cocacola.es:80/cab/InstaladorUniversal.exe), [Niue](https://web.archive.org/web/*/http://www.redzone.no:80/uploads/cab/InstaladorBetyByte.Universal.NO.exe), [Filandes](https://web.archive.org/web/*/http://www.redzone.fi:80/uploads/cab/InstaladorBetyByte.Universal.FI.exe)  |  Hay varios ficheros de Assets incluyendo vestidor, tiene pinta de poder arrancar |
| RoadRider | ???? | [Dinamarca](https://web.archive.org/web/*/http://www.redzone.dk:80/uploads/cab/InstaladorBetyByte.RoadRaider.DK.exe), [Niue](https://web.archive.org/web/*/http://www.redzone.no:80/uploads/cab/InstaladorBetyByte.RoadRaider.NO.exe), [Filandes]() | Desconocido |
| Vestidor | vestidor | Se incluye con todos los juegos de cocacola | Posibilidad que esten mas o menos actualizados dependiendo del instalador |
| SnowBattle | ???? | [Spanish (2003)](https://web.archive.org/web/*/http://download.cocacola.es:80/snowbattle/Updater_es.exe), [Spanish](https://web.archive.org/web/*/http://download.cocacola.es:80/descargas/snowbattle/updater.exe), [Dinamarca](http://download.cocacola.es/snowbattle/Updater_dk.exe), [Niue](https://web.archive.org/web/*/http://download.cocacola.es:80/snowbattle/Updater_nu.exe) | Es un Updater Stub. Se requiere de alguien con los ficheros instalados,  |
| SummerBattle | ???? | [Spanish](https://web.archive.org/web/*/http://download.cocacola.es:80/descargas/summerbattle/updater.exe)| Es un Updater Stub. Se requiere de alguien con los ficheros instalados |

???
https://web.archive.org/web/*/http://www.redzone.dk:80/uploads/cab/instaladorbetybyteuk.cab

## Ficheros/Assets Internos (.pak)

De momento, No se ha podido extraer/desencriptado ningun fichero, los ficheros de assets estan formato ".pak" que los contenidos no corresponden a ningun formato conocido y no hay un claro delimitador de datos entre fichero y fichero, asi que probablemente los offsets y inicio de secuencia esten en el header del fichero (cuales ya muestran los nombres de los ficheros dentro de .pak) pero probablemente habra que saber el metodo de desencriptacion.

## Comportamientos

El Updater.exe puede eliminar clima.exe, el update devuelve como exitcode con un 1.  
Para mas precaucion, usar un ejecutable como que devuelva un 0 con nombre de updater.exe.

## URL Conocidas

- cocacola.es - Obviamente web Oficial  
- download.cocacola.es - CDN de Cocacola/BetyByte (Todos los enlaces de Snowbattle internacional redireccionan a aqui)  
- www.redzone.dk - Version de Dinamarca del Movimiento Cocacola
- www.redzone.no
- www.redzone.fi 
- www.redzone.nu

## Articulos & Referencias
- [Caso Cocacola (PDF)](https://www.scribd.com/document/255636588/caso-cocacola-es-pdf) Por el Instituto de Empresa
- [COCA-COLA es de los consumidores](http://pdfs.wke.es/9/5/7/6/pd0000019576.pdf) por Maribel REYES MORENO publicado en "MK Marketing+Ventas" Nº 217 Octubre de 2006. (Pág. 42)
- [LOS EFICACES efectos dela Comunidad de COCA-COLA](http://pdfs.wke.es/9/3/4/4/pd0000019344.pdf) por Josep Alet Vilaginés publicado en “MK Marketing+Ventas”, Nº 192, Junio de 2004. 
- [Linea de Tiempo de Bety-Byte](https://www.slideshare.net/crissbel/coca-cola-power-point?next_slideshow=37618091) Por la misma BetyByte
- [COCACOLA.ES UN REPASO A LA HISTORIA DE COCA-COLA EN ESPAÑA](https://docplayer.es/20341833-Cocacola-es-un-repaso-a-la-historia-de-coca-cola-en-espana-si1-120.html) por la IE Business School
## Videos

- [SnowBattle](https://www.youtube.com/watch?v=v23GkhJE-A0) resubido por mi, el autor original lo puso en privado.  
- [RedZone - MiniCD](https://www.youtube.com/watch?v=V3ocJnNix6s) Este Video que muestra un MiniCD es el contenido rescatado mas reciente a pesar de no estar archivado de Archive.org  
- [Spot de Dinamarca de RedZone](https://www.youtube.com/watch?v=WFKF2NrEew8) - Equivalente al movimiento cocacola.  

## Proyectos de Cocacola similares internacionalmente

- [MyCoke](https://en.wikipedia.org/wiki/MyCoke) - Alternativa Estadounidense parecida a Habbo Hotel pero usando el Motor de Sulake  
- Ciudad Konec-t - La Alternativa mexicana mas proxima a Habbo Hotel