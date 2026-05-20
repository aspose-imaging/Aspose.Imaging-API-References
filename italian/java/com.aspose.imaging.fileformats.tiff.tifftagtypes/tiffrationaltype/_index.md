---
title: "TiffRationalType"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il tipo rationale TIFF."
type: docs
weight: 19
url: /it/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffRationalType extends TiffCommonArrayType
```

Il tipo rationale TIFF.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffRationalType(int tagId)](#TiffRationalType-int-) | Inizializza una nuova istanza della classe `TiffRationalType`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getValues()](#getValues--) | Ottiene o imposta i valori. |
| [setValues(TiffRational[] value)](#setValues-com.aspose.imaging.fileformats.tiff.TiffRational---) | Ottiene o imposta i valori. |
| [getValuesContainer()](#getValuesContainer--) | Ottiene il contenitore dei valori. |
| [getElementSize()](#getElementSize--) | Ottiene la dimensione dell'elemento in byte. |
| [getTagType()](#getTagType--) | Ottiene il tipo del tag. |
| [getValue()](#getValue--) | Ottiene o imposta il valore che questo tipo di dati contiene. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Ottiene o imposta il valore che questo tipo di dati contiene. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Scrive i dati aggiuntivi del tag. |
### TiffRationalType(int tagId) {#TiffRationalType-int-}
```
public TiffRationalType(int tagId)
```


Inizializza una nuova istanza della classe `TiffRationalType`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tagId | int | L'ID del tag. |

### getValues() {#getValues--}
```
public TiffRational[] getValues()
```


Ottiene o imposta i valori.

Valore: I valori.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setValues(TiffRational[] value) {#setValues-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setValues(TiffRational[] value)
```


Ottiene o imposta i valori.

Valore: I valori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Ottiene il contenitore dei valori.

Valore: Il contenitore dei valori.

**Returns:**
com.aspose.ms.System.Array
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Ottiene la dimensione dell'elemento in byte.

Valore: La dimensione dell'elemento in byte.

**Returns:**
byte
### getTagType() {#getTagType--}
```
public int getTagType()
```


Ottiene il tipo del tag.

Valore: Il tipo di tag.

**Returns:**
int
### getValue() {#getValue--}
```
public Object getValue()
```


Ottiene o imposta il valore che questo tipo di dati contiene.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Ottiene o imposta il valore che questo tipo di dati contiene.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object |  |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public long writeAdditionalData(TiffStreamWriter dataStream)
```


Scrive i dati aggiuntivi del tag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | Il flusso di dati. |

**Returns:**
long - I byte effettivamente scritti.
