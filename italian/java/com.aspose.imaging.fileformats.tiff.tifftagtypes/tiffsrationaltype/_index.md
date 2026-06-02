---
title: "TiffSRationalType"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il tipo tiff signed rational."
type: docs
weight: 23
url: /it/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffsrationaltype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffSRationalType extends TiffCommonArrayType
```

Il tipo tiff signed rational.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffSRationalType(int tagId)](#TiffSRationalType-int-) | Inizializza una nuova istanza della classe `TiffSRationalType`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getValues()](#getValues--) | Ottiene o imposta i valori. |
| [setValues(TiffSRational[] value)](#setValues-com.aspose.imaging.fileformats.tiff.TiffSRational---) | Ottiene o imposta i valori. |
| [getValuesContainer()](#getValuesContainer--) | Ottiene il contenitore dei valori. |
| [getElementSize()](#getElementSize--) | Ottiene la dimensione dell'elemento in byte. |
| [getTagType()](#getTagType--) | Ottiene il tipo del tag. |
| [getValue()](#getValue--) | Ottiene o imposta il valore che questo tipo di dati contiene. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Ottiene o imposta il valore che questo tipo di dati contiene. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Scrive i dati aggiuntivi del tag. |
### TiffSRationalType(int tagId) {#TiffSRationalType-int-}
```
public TiffSRationalType(int tagId)
```


Inizializza una nuova istanza della classe `TiffSRationalType`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tagId | int | L'ID del tag. |

### getValues() {#getValues--}
```
public TiffSRational[] getValues()
```


Ottiene o imposta i valori.

Valore: I valori.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffSRational[]
### setValues(TiffSRational[] value) {#setValues-com.aspose.imaging.fileformats.tiff.TiffSRational---}
```
public void setValues(TiffSRational[] value)
```


Ottiene o imposta i valori.

Valore: I valori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [TiffSRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

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
