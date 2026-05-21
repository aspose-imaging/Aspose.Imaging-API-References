---
title: "WmfBitmapBaseHeader"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La clase base de encabezado de bitmap."
type: docs
weight: 14
url: /es/java/com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public abstract class WmfBitmapBaseHeader extends MetaObject
```

La clase base de encabezado de bitmap.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfBitmapBaseHeader()](#WmfBitmapBaseHeader--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getHeaderSize()](#getHeaderSize--) | Obtiene o establece un entero sin signo de 32 bits que define el tamaño de este objeto, en bytes. |
| [setHeaderSize(int value)](#setHeaderSize-int-) | Obtiene o establece un entero sin signo de 32 bits que define el tamaño de este objeto, en bytes. |
| [getPlanes()](#getPlanes--) | Obtiene o establece un entero sin signo de 16 bits que define el número de `planes` para el dispositivo de destino. |
| [setPlanes(short value)](#setPlanes-short-) | Obtiene o establece un entero sin signo de 16 bits que define el número de `planes` para el dispositivo de destino. |
| [getBitCount()](#getBitCount--) | Obtiene o establece un entero sin signo de 16 bits que define el formato de cada píxel y el número máximo de colores en el DIB. |
| [setBitCount(short value)](#setBitCount-short-) | Obtiene o establece un entero sin signo de 16 bits que define el formato de cada píxel y el número máximo de colores en el DIB. |
### WmfBitmapBaseHeader() {#WmfBitmapBaseHeader--}
```
public WmfBitmapBaseHeader()
```


### getHeaderSize() {#getHeaderSize--}
```
public int getHeaderSize()
```


Obtiene o establece un entero sin signo de 32 bits que define el tamaño de este objeto, en bytes.

**Returns:**
int
### setHeaderSize(int value) {#setHeaderSize-int-}
```
public void setHeaderSize(int value)
```


Obtiene o establece un entero sin signo de 32 bits que define el tamaño de este objeto, en bytes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Un entero sin signo de 16 bits que define el número de `planes` para el dispositivo de destino. Este valor DEBE ser 0x0001. |

### getPlanes() {#getPlanes--}
```
public short getPlanes()
```


Obtiene o establece un entero sin signo de 16 bits que define el número de `planes` para el dispositivo de destino. Este valor DEBE ser 0x0001.

**Returns:**
short - un entero sin signo de 16 bits que define el número de `planes` para el dispositivo de destino.
### setPlanes(short value) {#setPlanes-short-}
```
public void setPlanes(short value)
```


Obtiene o establece un entero sin signo de 16 bits que define el número de `planes` para el dispositivo de destino. Este valor DEBE ser 0x0001.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short | un entero sin signo de 16 bits que define el número de `planes` para el dispositivo de destino. Este valor DEBE ser \* 0x0001. |

### getBitCount() {#getBitCount--}
```
public short getBitCount()
```


Obtiene o establece un entero sin signo de 16 bits que define el formato de cada píxel y el número máximo de colores en el DIB. Este valor DEBE estar en la enumeración `BitCount` (sección 2.1.1.3).

**Returns:**
short - un entero sin signo de 16 bits que define el formato de cada píxel y el número máximo de colores en el DIB.
### setBitCount(short value) {#setBitCount-short-}
```
public void setBitCount(short value)
```


Obtiene o establece un entero sin signo de 16 bits que define el formato de cada píxel y el número máximo de colores en el DIB. Este valor DEBE estar en la enumeración `BitCount` (sección 2.1.1.3).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short | un entero sin signo de 16 bits que define el formato de cada píxel y el número máximo de colores en el DIB. |

