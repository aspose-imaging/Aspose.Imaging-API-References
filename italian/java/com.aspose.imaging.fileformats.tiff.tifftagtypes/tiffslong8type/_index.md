---
title: "TiffSLong8Type"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il tipo TIFF senza segno a 64 bit."
type: docs
weight: 21
url: /it/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public class TiffSLong8Type extends TiffCommonArrayType
```

Il tipo TIFF senza segno a 64 bit.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffSLong8Type(int tagId)](#TiffSLong8Type-int-) | Inizializza una nuova istanza della classe [TiffSLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getValues()](#getValues--) | Ottiene i valori. |
| [setValues(long[] values)](#setValues-long---) | Imposta i valori. |
| [getValuesContainer()](#getValuesContainer--) | Ottiene il contenitore dei valori. |
| [getTagType()](#getTagType--) | Ottiene il tipo del tag. |
| [getValue()](#getValue--) | Ottiene il valore contenuto da questo tipo di dati. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Ottiene il valore contenuto da questo tipo di dati. |
| [getElementSize()](#getElementSize--) | Ottiene la dimensione dell'elemento. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Scrive i dati aggiuntivi del tag. |
### TiffSLong8Type(int tagId) {#TiffSLong8Type-int-}
```
public TiffSLong8Type(int tagId)
```


Inizializza una nuova istanza della classe [TiffSLong8Type](../../com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffslong8type).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tagId | int | L'ID del tag. |

### getValues() {#getValues--}
```
public final long[] getValues()
```


Ottiene i valori.

Valore: I valori del tag.

**Returns:**
long[] - i valori.
### setValues(long[] values) {#setValues-long---}
```
public void setValues(long[] values)
```


Imposta i valori.

Valore: I valori del tag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valori | long[] | I valori. |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Ottiene il contenitore dei valori.

**Returns:**
com.aspose.ms.System.Array - contenitore dei valori.
### getTagType() {#getTagType--}
```
public int getTagType()
```


Ottiene il tipo del tag.

Valore: Il tipo di tag.

**Returns:**
int - il tipo di tag.
### getValue() {#getValue--}
```
public Object getValue()
```


Ottiene il valore contenuto da questo tipo di dati.

**Returns:**
java.lang.Object - il valore che questo tipo di dati contiene.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Ottiene il valore contenuto da questo tipo di dati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object | Il valore che questo tipo di dati contiene. |

### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Ottiene la dimensione dell'elemento.

**Returns:**
byte - dimensione dell'elemento.
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
