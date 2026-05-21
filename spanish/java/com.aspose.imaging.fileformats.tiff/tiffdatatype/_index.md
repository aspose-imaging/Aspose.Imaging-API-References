---
title: "TiffDataType"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El tipo de datos TIFF."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.tiff/tiffdatatype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

El tipo de datos TIFF.
## Métodos

| Método | Descripción |
| --- | --- |
| [getElementSize()](#getElementSize--) | Obtiene el tamaño del elemento en bytes. |
| [getDataSize()](#getDataSize--) | Obtiene el tamaño del valor de la etiqueta. |
| [getCount()](#getCount--) | Obtiene la cantidad de elementos. |
| [getId()](#getId--) | Obtiene el id de la etiqueta como número. |
| [getTagId()](#getTagId--) | Obtiene el id de la etiqueta. |
| [getTagType()](#getTagType--) | Obtiene el tipo de etiqueta. |
| [getAlignedDataSize(byte sizeOfTagValue)](#getAlignedDataSize-byte-) | Obtiene el tamaño de los datos alineado a un límite de 4 bytes (int) o 8 bytes (long). |
| [getAdditionalDataSize(byte sizeOfTagValue)](#getAdditionalDataSize-byte-) | Obtiene el tamaño adicional del valor de la etiqueta en bytes (en caso de que la etiqueta no pueda contener todo el valor). |
| [getValue()](#getValue--) | Obtiene el valor que contiene este tipo de datos. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Establece el valor que contiene este tipo de datos. |
| [isValid()](#isValid--) | Obtiene un valor que indica si los datos de la etiqueta son válidos. |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-long-) | Lee los datos de la etiqueta. |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.imaging.fileformats.tiff.TiffDataType-) | Compara la instancia actual con otro objeto del mismo tipo y devuelve un entero que indica si la instancia actual precede, sigue o se encuentra en la misma posición en el orden de clasificación que el otro objeto. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [deepClone()](#deepClone--) | Realiza una clonación profunda de esta instancia. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | Escribe los datos de la etiqueta. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Escribe los datos adicionales de la etiqueta. |
| [toString()](#toString--) | Devuelve una `System.String` que representa esta instancia. |
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Obtiene el tamaño del elemento en bytes.

**Returns:**
byte - el tamaño del elemento en bytes.
### getDataSize() {#getDataSize--}
```
public long getDataSize()
```


Obtiene el tamaño del valor de la etiqueta.

**Returns:**
long - el tamaño del valor de la etiqueta.
### getCount() {#getCount--}
```
public abstract long getCount()
```


Obtiene la cantidad de elementos.

Valor: el recuento de elementos.

**Returns:**
long - el recuento de elementos.
### getId() {#getId--}
```
public final int getId()
```


Obtiene el id de la etiqueta como número.

**Returns:**
int - id de etiqueta como número.
### getTagId() {#getTagId--}
```
public int getTagId()
```


Obtiene el id de la etiqueta.

**Returns:**
int - el id de la etiqueta.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


Obtiene el tipo de etiqueta.

**Returns:**
int - el tipo de etiqueta.
### getAlignedDataSize(byte sizeOfTagValue) {#getAlignedDataSize-byte-}
```
public final long getAlignedDataSize(byte sizeOfTagValue)
```


Obtiene el tamaño de los datos alineado a un límite de 4 bytes (int) o 8 bytes (long).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sizeOfTagValue | byte | Tamaño del valor de la etiqueta. |

**Returns:**
long - el tamaño de los datos alineados en bytes.
### getAdditionalDataSize(byte sizeOfTagValue) {#getAdditionalDataSize-byte-}
```
public long getAdditionalDataSize(byte sizeOfTagValue)
```


Obtiene el tamaño adicional del valor de la etiqueta en bytes (en caso de que la etiqueta no pueda contener todo el valor).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sizeOfTagValue | byte | Tamaño del valor de la etiqueta: 4 u 8 para BigTiff. |

**Returns:**
long - el tamaño de los datos adicionales en bytes.
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Obtiene el valor que contiene este tipo de datos.

**Returns:**
java.lang.Object - el valor.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Establece el valor que contiene este tipo de datos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object | El valor. |

### isValid() {#isValid--}
```
public boolean isValid()
```


Obtiene un valor que indica si los datos de la etiqueta son válidos. La etiqueta válida contiene datos que pueden preservarse. La etiqueta inválida no puede almacenarse.

**Returns:**
boolean - `true` si los datos de la etiqueta son válidos; de lo contrario, `false`.
### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


Lee los datos de la etiqueta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) | El flujo de datos. |
| posición | long | La posición de la etiqueta. |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - The read tag.
### compareTo(TiffDataType obj) {#compareTo-com.aspose.imaging.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


Compara la instancia actual con otro objeto del mismo tipo y devuelve un entero que indica si la instancia actual precede, sigue o se encuentra en la misma posición en el orden de clasificación que el otro objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Un objeto para comparar con esta instancia. |

**Returns:**
int - Un entero con signo de 32 bits que indica el orden relativo de los objetos que se comparan. El valor de retorno tiene estos significados: Valor Significado Menor que cero Esta instancia es menor que `obj`. Cero Esta instancia es igual a `obj`. Mayor que cero Esta instancia es mayor que `obj`.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


Realiza una clonación profunda de esta instancia.

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


Escribe los datos de la etiqueta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | El flujo de datos. |
| additionalDataOffset | long | El desplazamiento donde escribir datos adicionales. |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


Escribe los datos adicionales de la etiqueta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | El flujo de datos. |

**Returns:**
long - Los bytes reales escritos.
### toString() {#toString--}
```
public String toString()
```


Devuelve una `System.String` que representa esta instancia.

**Returns:**
java.lang.String - Un `System.String` que representa esta instancia.
