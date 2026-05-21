---
title: "EmfPlusSetTsClip"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusSetTSClip especifica áreas de recorte en el contexto del dispositivo gráfico para un servidor de terminales."
type: docs
weight: 66
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetTsClip extends EmfPlusTerminalServerRecordType
```

El registro EmfPlusSetTSClip especifica áreas de recorte en el contexto del dispositivo gráfico para un servidor de terminales.

El esquema de compresión para los datos en este registro utiliza el siguiente algoritmo. Cada punto de cada rectángulo se codifica en un solo byte o en 2 bytes. Si el punto se codifica en un solo byte, el bit más alto (0x80) del byte DEBE estar establecido, y el valor es un número con signo representado por los 7 bits inferiores. Si el bit más alto no está establecido, entonces el valor se codifica en 2 bytes, con el byte de orden superior codificado en los 7 bits inferiores del primer byte, y el valor del byte de orden inferior codificado en el segundo byte. Cada punto se codifica como la diferencia entre el punto del rectángulo actual y el punto del rectángulo anterior. El punto inferior del rectángulo se codifica como la diferencia entre la coordenada inferior y la coordenada superior en el rectángulo actual.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusSetTsClip(EmfPlusRecord source)](#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusSetTsClip`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCompressed()](#getCompressed--) | Obtiene un valor que indica si este `EmfPlusSetTsClip` está comprimido. |
| [getNumRects()](#getNumRects--) | Obtiene el número de rects. |
| [getRects()](#getRects--) | Obtiene o establece una matriz de rectángulos NumRects que definen áreas de recorte. |
| [setRects(Rectangle[] value)](#setRects-com.aspose.imaging.Rectangle---) | Obtiene o establece una matriz de rectángulos NumRects que definen áreas de recorte. |
### EmfPlusSetTsClip(EmfPlusRecord source) {#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTsClip(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusSetTsClip`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Obtiene un valor que indica si este `EmfPlusSetTsClip` está comprimido. Este bit especifica el formato de los datos de rectángulo en el campo rects. Si está activado, cada rectángulo se define en 4 bytes. Si está desactivado, cada rectángulo se define en 8 bytes.

Valor: `true` si está comprimido; de lo contrario, `false`.

**Returns:**
boolean
### getNumRects() {#getNumRects--}
```
public short getNumRects()
```


Obtiene el número de rects. Este campo especifica la cantidad de rectángulos que están definidos en el campo rect.

Valor: El número de rects.

**Returns:**
short
### getRects() {#getRects--}
```
public Rectangle[] getRects()
```


Obtiene o establece una matriz de rectángulos NumRects que definen áreas de recorte. El formato de estos datos está determinado por el bit C en el campo Flags.

Valor: Los rects.

**Returns:**
com.aspose.imaging.Rectangle[]
### setRects(Rectangle[] value) {#setRects-com.aspose.imaging.Rectangle---}
```
public void setRects(Rectangle[] value)
```


Obtiene o establece una matriz de rectángulos NumRects que definen áreas de recorte. El formato de estos datos está determinado por el bit C en el campo Flags.

Valor: Los rects.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

