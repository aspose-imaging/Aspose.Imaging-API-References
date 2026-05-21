---
title: "EmfUniversalFontId"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto UniversalFontId define un mecanismo para identificar fuentes en metarchivos EMF."
type: docs
weight: 37
url: /es/java/com.aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfUniversalFontId extends EmfObject
```

El objeto UniversalFontId define un mecanismo para identificar fuentes en metarchivos EMF.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfUniversalFontId()](#EmfUniversalFontId--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getChecksum()](#getChecksum--) | Obtiene o establece un entero sin signo de 32 bits que es la suma de verificación de la fuente. |
| [setChecksum(int value)](#setChecksum-int-) | Obtiene o establece un entero sin signo de 32 bits que es la suma de verificación de la fuente. |
| [getIndex()](#getIndex--) | Obtiene o establece un entero sin signo de 32 bits que es un índice asociado al objeto de fuente. |
| [setIndex(int value)](#setIndex-int-) | Obtiene o establece un entero sin signo de 32 bits que es un índice asociado al objeto de fuente. |
### EmfUniversalFontId() {#EmfUniversalFontId--}
```
public EmfUniversalFontId()
```


### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Obtiene o establece un entero sin signo de 32 bits que es la suma de verificación de la fuente. El valor de la suma de verificación tiene los siguientes significados. 0x00000000 El objeto es una fuente de dispositivo. 0x00000001 El objeto es una fuente Type 1 que ha sido instalada en la máquina cliente y es enumerada por el controlador de impresora PostScript como una fuente de dispositivo. 0x00000002 El objeto no es una fuente sino un rasterizador Type 1. 3 \\u2264 valor El objeto es una fuente bitmap, vectorial o TrueType, o una fuente rasterizada Type 1 que fue creada por un rasterizador Type 1.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Obtiene o establece un entero sin signo de 32 bits que es la suma de verificación de la fuente. El valor de la suma de verificación tiene los siguientes significados. 0x00000000 El objeto es una fuente de dispositivo. 0x00000001 El objeto es una fuente Type 1 que ha sido instalada en la máquina cliente y es enumerada por el controlador de impresora PostScript como una fuente de dispositivo. 0x00000002 El objeto no es una fuente sino un rasterizador Type 1. 3 \\u2264 valor El objeto es una fuente bitmap, vectorial o TrueType, o una fuente rasterizada Type 1 que fue creada por un rasterizador Type 1.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getIndex() {#getIndex--}
```
public int getIndex()
```


Obtiene o establece un entero sin signo de 32 bits que es un índice asociado al objeto de fuente. El significado de este campo está determinado por el tipo de fuente.

**Returns:**
int
### setIndex(int value) {#setIndex-int-}
```
public void setIndex(int value)
```


Obtiene o establece un entero sin signo de 32 bits que es un índice asociado al objeto de fuente. El significado de este campo está determinado por el tipo de fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

